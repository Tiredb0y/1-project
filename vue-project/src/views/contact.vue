<template>
    <div class="cotact">
        <form class="ffa">
       <center>
        <h1>Feedback</h1>
        <p>First Name</p><input placeholder="Your first name" >
       <p>last name</p> <input placeholder="your last name">
        <p>password</p> <input placeholder="your password">
            <p>Email</p><input placeholder="your Email">
             <p>Don't Forget me</p><input type="radio" style="margin-bottom: 20px;">  
             <br>
             <input type="submit">
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
    width: 500px;
    height: 500px   ;
    justify-content: center;
    background-color: rgb(78, 77, 77);
    margin-bottom: 20px;
    margin-top: 20px;
    display: flexbox;
}
</style>
<script setup>

</script>