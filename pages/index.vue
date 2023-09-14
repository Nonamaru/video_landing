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

        <div class="body">
            <div class="face">
                <FaceView />
            </div>
        </div>
        
        <div class="footer">
            <div class="logo-contacts">
                <text>LOGO</text>
                <a href = "mailto:abc@example.com?subject=Feedback&body=Message">a.kataev@gmail.com</a>
                <a href="tel=+79124734699">+79124734699</a>
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
    border-radius: var(--main-border-radius);
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
    border-radius: var(--small-border-radius);
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
.number:hover{color: var(--blue-color)}
/*------*/


/*BODY*/
.body{
    width: 100%;
    border: 1px solid black;
}
/*----*/


/*FOOTER*/
.footer{
    margin-top: 10%;
    background-color: var(--white-color);
    display: grid;
    grid-template-columns: 50% 50%;
    grid-template-rows: 50% 50%;
    padding: 16px;
    border-radius: var(--main-border-radius);
}

.logo-contacts{
    grid-column: 1;
    grid-row: 1;
    display: flex;
    flex-direction: column;
    justify-content: left;
    font-size: 16px;
    font-weight: bold;
    gap: 10px;
}
.logo-contacts a{
    text-decoration: none;
    color: black;
}
.logo-contacts a:hover{color: var(--blue-color)}

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
.confidential-policy a{
    text-decoration: none;
    color: var( --gray-blue-color);
}
.confidential-policy a:hover{color: var(--blue-color)}

.address{
    grid-column: 2;
    grid-row: 2;
    display: flex;
    justify-content: right;
    font-size: 36px;
}
/*------*/
</style>