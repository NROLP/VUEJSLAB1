<template>
    <div class="home">
        <h1>Congrats you made it this far.</h1>
        <p>You can now proceed to link your manage page.</p>
    </div>

    <RouterLink to="/manage" class="link">Click me -> Manage</RouterLink>
</template>

<script>

export default {
    name: 'Home'
}
</script>

<style scoped>
/* Add your custom CSS styles here */

.home {
    background-color: #0A0A0A;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
    text-align: center;
}

h1 {
    font-size: 24px;
    color: #333;
}

p {
    font-size: 18px;
    color: #666;
}
.link {
    background-color: #F5F5F7;
    padding: 20px;
    border: 1px solid #15292B;
    border-radius: 5px;
    text-align: center;
}
</style>
