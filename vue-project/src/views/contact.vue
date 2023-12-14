<template>
    <div class="cotact">
        <form class="ffa">
       <center>
        <div style="margin-top: 20px;"><h1>Feedback</h1></div>
            <div><p>First Name</p><input type="text" placeholder="Your first name" ></div>
            <div><p>last name</p> <input type="text" placeholder="your last name"></div>
            <div><p>password</p> <input type="password" placeholder="your password"></div>
            <div><p>Email</p><input type="email" placeholder="your Email"></div>
            <div><p>Don't Forget me</p><input type="radio" style="margin-bottom: 20px;"></div>
            <div><input type="submit"></div>
       </center>
        </form>
    </div>
</template>

<style scoped>
.cotact{
    display: flex;
    justify-content: center;
}
.ffa{
    border-radius: 10px;
    width: 400px;
    height: 450px   ;
    justify-content: center;
    background-color: rgb(132, 132, 132);
    margin-bottom: 20px;
    margin-top: 20px;
    display: flexbox;
}
.ffa div{
margin-bottom: 20px;
}
.ffa input {
    background-color: none;
    border: none;
}
</style>
<script setup>

</script>