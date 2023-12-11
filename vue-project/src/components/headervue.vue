<script setup>

</script>
<template>
    <header>
       <div> <input type="text" class="inputsearch" placeholder="Search About ...."></div>
        <h1>First Project</h1>
            <div><img src="../icons8-logo.svg" alt=""></div>
        </header>

        <nav>
            <RouterLink to="/">Home</RouterLink>
            <RouterLink to="/about">About</RouterLink>
            <RouterLink to="/contact">Contact</RouterLink>
        </nav>
        
</template>
<style scoped>
        .inputsearch{
            height: 20px;
            width: 160px;
            
        }
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 15px;
            display: flex;
            justify-content: space-around;
            /* text-align: center; */
            align-items: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 10px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #555;
        }
</style>