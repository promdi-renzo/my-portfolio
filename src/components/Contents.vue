<template>
    <div class="container">
        <div class="main">
            <img src="https://picsum.photos/200" 
            alt="pic">
            <h1><b>Renzo Cabarios</b></h1>
            <p>An aspiring software engineer</p>
        </div>
        <div class="content">
            <h2><b>A man with options has power</b></h2>
        </div>
    </div>
</template>

<script>

export default {
    name: 'Contents',
    props:{
        picLink: String
    }

}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');


.container{
    font-family: 'Open Sans', sans-serif;
    text-align: center;
    box-shadow: 0 3px 10px rgb(0 0 0 / 0.2);
    padding: 80px 0px;
    margin: 10px 8%;
    width: 85%;
}
.main{

}

.main img{
    width: 40%;
    height: 200px;
}

.content{
    padding: 15px 0px;
    margin: 10px 10%;
    border-bottom: 1px solid #3D95D8;
    color: gray;
}


</style>