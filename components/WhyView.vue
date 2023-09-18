<template>
<div class="whyView-container">
    <h1 style="font-weight: var(--bold-font);">
        <text style="color: var(--orange-color)">Зачем</text>&nbsp;
        <text style="color: var(--black-color)">нужна</text>&nbsp;
        <text style="color: var(--orange-color)">система видеонаблюдения</text>
    </h1>
    <h3 style="color: var(--black-color)">Система видеонаблюдения позволяет:</h3>
    <div class="strong-sides">
        <div class="photo">photo</div>
        <div class="build">
            <div class="titledesc-left-block">
                <text class="title">Производить</text>
                <text class="desc">удаленный контроль рабочих процессов, трудовую дисциплину и контроль работы персонала. Усиление безопасности вашего объекта;</text>
            </div>
            <div class="card-photo">photo</div>
        </div>
        <div class="defence">
            <div class="titledesc-left-block">
                <text class="title">Защитить</text>
                <text class="desc">от несанкционарованного доступа и краж на территории офиса, склада, помещения;</text>
            </div>
            <div class="card-photo">photo</div>
        </div>
        <div class="warn">
            <div class="titledesc-left-block">
                <text class="title">Предупредить</text>
                <text class="desc">или раскрыть хищение или порчу имущества;</text>
            </div>
            <div class="card-photo">photo</div>
        </div>
        <div class="consider">
            <div class="card-photo">photo</div>
            <div class="titledesc-right-block">
                <text class="title">Учитывать</text>
                <text class="desc"></text>
            </div>
        </div>
        <div class="control">
            <div class="card-photo">photo</div>
            <div class="titledesc-right-block">
                <text class="title">Контроллировать</text>
                <text class="desc"></text>
            </div>
        </div>
        <div class="participate">
            <div class="card-photo">photo</div>
            <div class="titledesc-right-block">
                <text class="title">Установить</text>
                <text class="desc"></text>
            </div>
        </div>
        <div class="create">
            <div class="card-photo">photo</div>
            <div class="titledesc-right-block">
                <text class="title">Создать</text>
                <text class="desc"></text>
            </div>
        </div>
    </div>
</div>
</template>
<style scoped>
.whyView-container{
    font-weight: var(--bold-font);
    color: black;
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
    grid-template-columns: 35% 30% 35%;
    grid-template-rows: 1fr 1fr 1fr 1fr;
    margin-left: auto;
    margin-right: auto;
    border: 1px solid black;
    width: 90%;
}

.photo{
    border: 1px solid black;
    grid-column: 2;
    grid-row: 1/5;
}

.card-photo{
    margin-left: 5%;
    margin-right: 5%;
}
.titledesc-left-block{
    text-align: left;
}
.titledesc-right-block{
    text-align: right;
}

.build{
    border: 1px solid black;
    grid-column: 1;
    grid-row: 1/3;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}
.defence{
    border: 1px solid black;
    grid-column: 1;
    grid-row: 3;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}
.warn{
    border: 1px solid black;
    grid-column: 1;
    grid-row: 4;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}
.consider{
    border: 1px solid black;
    grid-column: 3;
    grid-row: 1;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}
.control{
    border: 1px solid black;
    grid-column: 3;
    grid-row: 2;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}
.participate{
    border: 1px solid black;
    grid-column: 3;
    grid-row: 3;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}
.create{
    border: 1px solid black;
    grid-column: 3;
    grid-row: 4;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}
</style>