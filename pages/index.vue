<template>
<div class="web-view">
    <div class="container">
        <div class="header">
            <div class="logo">LOGO</div>
            <div class="anchords">
                <div class="anchor">Услуги</div>
                <div class="anchor">Схема работы</div>
                <div class="anchor">Контакты</div>
            </div>
            <a class="number" href="tel=+79124734699">+79124734699</a>
        </div>
        <div class="body"></div>
        <div class="footer">
            <div class="logo-contacts">
                <text>LOGO</text>
                <text>EMAIN</text>
                <text>NUMBER</text>
            </div>
            <div class="footer-anchords">
                <div class="footer-anchor">Услуги</div>
                <div class="footer-anchor">Схема работы</div>
                <div class="footer-anchor">Контакты</div>
            </div>
            <div class="confidential-policy">
                <a href="#">Политика конфеденциальности</a>
            </div>
            <div class="address">Екатеринбург, Кулибина 2, офис 302</div>
        </div>
    </div>
</div>
</template>
<style scoped>
/*MAIN*/
.web-view{
    width: 100vw;
}
.container{
    width: 1200px;
    margin-left: auto;
    margin-right: auto;
    display: flex;
    flex-direction: column;
}
/*----*/


/*HEADER*/
.header{
    border-radius: 16px;
    background-color: var(--white-color);
    padding: 8px 16px;
    margin-top: 1%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}
.anchords{
    display: flex;
    flex-direction: row;
    gap: 10px;
}
.anchor{
    border-radius: 8px;
    background-color: var(--light-gray-color);
    padding: 4px 8px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.number{
    text-decoration: none;
    color: black;
}
/*------*/


/*FOOTER*/
.footer{
    margin-top: 10%;
    background-color: var(--white-color);
    display: grid;
    grid-template-columns: 50% 50%;
    grid-template-rows: 50% 50%;
    padding: 16px;
    border-radius: 16px;
}

.logo-contacts{
    grid-column: 1;
    grid-row: 1;
    display: flex;
    flex-direction: column;
    justify-content: left;
    font-size: 28px;
}

.footer-anchords{
    grid-column: 2;
    grid-row: 1;
    display: flex;
    flex-direction: row;
    gap: 10px;
    justify-content: right;
    align-items: start;
}
.footer-anchor{
    border-radius: 8px;
    background-color: var(--light-gray-color);
    padding: 4px 8px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.confidential-policy{
    grid-column: 1;
    grid-row: 2;
    display: flex;
    justify-content: left;
    align-items: end;
}

.address{
    grid-column: 2;
    grid-row: 2;
    display: flex;
    justify-content: right;
    font-size: 36px;
}
/*------*/
</style>