<template>
<div class="container">
    <div class="first">1</div>
    <div class="second">2</div>
    <div class="photo">3</div>
</div>
</template>
<style scoped>
.container{
    display: grid;
    grid-template-columns: 70% 30%;
    grid-template-rows: 50% 50%;
    gap: 20px;
}
.first{
    grid-column: 1;
    grid-row: 1;
    border: 1px solid black;
    border-radius: var(--main-border-radius);
    background-color: var(--white-color);
    padding: 16px;
}
.second{
    grid-column: 1;
    grid-row: 2;
    border: 1px solid black;
    border-radius: var(--main-border-radius);
    background-color: var(--white-color);
    padding: 16px;
}
.photo{
    grid-column: 2;
    grid-row: 1/3;
    border: 1px solid black;
    border-radius: var(--main-border-radius);
    background-color: var(--white-color);
    padding: 16px;
}
</style>