<template>
    <div class="container">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Projects</a></li>
            <li><a href="#">Contact</a></li>
         </ul>
    </div>
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');

.container{
    display: flex;
    flex-direction: row;
    justify-content: center;
    box-shadow: 0 3px 10px rgb(0 0 0 / 0.2);
    padding: 20px;
    background-color: #3D95D8;
}

ul{
    display: flex;
    flex-direction: row; 
}


li{
    list-style-type: none;
}
li a{

    margin: 0px 20px;
    color: white;
    text-decoration: none;
    font-family: 'Open Sans', sans-serif;
    font-weight: bold;
    font-size: 24px;
}
</style>