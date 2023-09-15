<template>
<div class="whyView-container">
    <h1 style="font-weight: var(--bold-font);">
        <text style="color: var(--orange-color)">Зачем</text>&nbsp;
        <text style="color: var(--black-color)">нужна</text>&nbsp;
        <text style="color: var(--orange-color)">система видеонаблюдения</text>
    </h1>
    <h3 style="color: var(--black-color)">Система видеонаблюдения позволяет:</h3>
    <div class="strong-sides">
    </div>
</div>
</template>
<style scoped>
.whyView-container{
    font-weight: var(--bold-font);
}
h1{
    text-align: center;
}
h3{
    text-align: center;
    margin-top: 1vh;
    margin-bottom: 5vh;
}
.strong-sides{
    display: grid;
    grid-template-columns: 40% 20% 40%;
    grid-template-rows: 1fr 1fr 1fr 1fr;
}
</style>