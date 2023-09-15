<template>
<div class="postheader-container">
    <div class="picture"><img src="../assets/cameraface.png"></div>
    <h1 class="title">Монтаж Видеонаблюдения<br />в Екатеринбурге</h1>
    <text class="description">Получите бесплатную консультацию от специалистов.<br />Перезвоним за минуту, посчитаем за час,<br />смонтируем за сутки!</text>
    <div class="feedback-button">
        <div class="button"><text>Оставить заявку</text></div>
    </div>
</div>
</template>
<style scoped>
.postheader-container{
    width: 70vw;
    margin-left: auto;
    margin-right: auto;
    display: grid;
    grid-template-columns: 50% 50%;
    grid-template-rows: 1fr 1fr 1fr;
    font-weight: var(--bold-font);
    text-align: center;
    margin-bottom: 32px;
}

.picture{
    color: var(--gray-color);
    grid-column: 1;
    grid-row: 1/4;
    border-radius: 16px;
}
.picture img{
    width: 100%;
    height: 100%;
    object-fit: contain;
}
.title{
    color: var(--white-color);
    grid-column: 2;
    grid-row: 1;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
}
.description{
    color: var(--gray-color);
    grid-column: 2;
    grid-row: 2;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
}
.feedback-button{
    grid-column: 2;
    grid-row: 3;
    display: flex;
    flex-direction: column;
    justify-content: center;
}
.button{
    border: 3px solid #ff6600c0;
    border-radius: 32px;
    width: 50%;
    margin-left: auto;
    margin-right: auto;
    padding: 16px 32px;
}
</style>