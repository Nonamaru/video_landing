<template>
<div class="face-view">
    <div class="first">1</div>
    <div class="second">2</div>
    <div class="photo">
        <img src="../assets/face_camera.jpg" />
    </div>
</div>
</template>
<style scoped>
.face-view{
    display: grid;
    grid-template-columns: 55% 45%;
    grid-template-rows: 50% 50%;
}
.first{
    grid-column: 1;
    grid-row: 1;
    border-radius: var(--main-border-radius);
    background-color: var(--white-color);
    padding: 16px;
}
.second{
    grid-column: 1;
    grid-row: 2;
    border-radius: var(--main-border-radius);
    background-color: var(--white-color);
    padding: 16px;
}
.photo{
    grid-column: 2;
    grid-row: 1/3;
    /* height: 400px; */
    border-radius: var(--main-border-radius);
    background-color: var(--white-color);
}
.photo img{
    width: 100%;
    height: 100%;
    object-fit: contain;
    border-radius: var(--main-border-radius);
}
</style>