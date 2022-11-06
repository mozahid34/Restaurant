<template>
<img class="logo" src="../assets/resto-logo.jpg" alt="">
    <h1>SignUp  </h1>

    <div class="form" >
        <input type="text" placeholder="Name">
        <input type="text" placeholder="Email">
        <input type="password" placeholder="Password">
        <button>Submit</button>
    </div>
</template>

<script>
export default {
    name: 'SignUp'
    
}
</script>

<style scoped>
.logo {
    width: 100px;
}
/* .form {
    display: flex;
    flex-direction: column;
    gap: 15px;
} */
.form input {
    display: block;
    width: 350px;
    height: 30px;
    margin: auto;
    margin-bottom: 15px;
}
.form button {
    display: block;
    width: 350px;
    height: 30px;
    margin: auto;
    background: rgba(153, 205, 50, 0.678);
    
}
button:hover {
    cursor: pointer;

}
</style>