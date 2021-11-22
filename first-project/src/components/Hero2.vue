<template>
    <div class="Hero-container">
        <div class="container-text">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Odio commodi aut, aliquid praesentium blanditiis ullam tempora? At blanditiis magnam omnis ad officiis ex harum veniam repellendus fuga, enim commodi voluptatibus?
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorum labore eveniet inventore! Repudiandae at aperiam autem. Quaerat eius illum fugit repellendus nisi tenetur quae voluptatem, minus odio in libero. Neque.
            </p>
        </div>
         <div class="img-container">
             <img src="https://picsum.photos/id/1/200/300" alt="">
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .Hero-container{
        display: flex;
        background-color: #000;
        color: #fff;
        flex-direction: row-reverse;
        margin-top: 30px;
    }

    .container-text{
        width: 50%;
        margin-right: 50px;
    }
    .container-text p {
        line-height: 30px;
    }

    .img-container{
        margin: 10px 0 ;
        height: 250px;
        width: 50%;
        display: flex;
        justify-content: center;
    }

    .img-container img{
        object-fit: contain;
        width: 50%;
        height: 100%;
    }
</style>