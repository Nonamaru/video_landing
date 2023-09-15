<template>
<div class="container">
    <div class="header">
        <div class="logo">LOGO</div>
        <div class="anchords">
            <a href="#" class="anchor">odin</a>
            <a href="#" class="anchor">dva</a>
            <a href="#" class="anchor">tri</a>
        </div>
        <div class="number-feedback">
            <div class="number-icon">
                <Icon class="icon" icon="gg:phone" />
                <a href="tel:+79124734699">+7 (912) 473 46-99</a>
            </div>
            <div class="feedback">
                <text>Заказать звонок</text>
            </div>
        </div>
    </div>
    <div class="body">
        <div class="first">1</div>
        <div class="which">2</div>
        <div class="calculate">3</div>
        <div class="youcantake">4</div>
    </div>
    <div class="footer">
        <div class="footer-title">
            <text style="color: var(--orange-color)">Остались вопросы?</text>&nbsp;
            <text style="color: var(--white-color)">Позвоните по телефону</text>
        </div>
        <a href="tel:+79124734699" class="footer-number">+7 (912) 473 46-99</a>
        <div class="footer-call-feedback">
            <text class="feedback-title">Или заполните форму и мы вам перезвоним</text>
            <div class="inputs-politics">
                <div class="inputs">
                    <Icon class="footer-icon" icon="material-symbols:person" />
                    <input type="text" placeholder="Имя" />
                </div>
                <div class="inputs">
                    <Icon class="footer-icon" icon="bxs:phone" />
                    <input type="text" placeholder="Телефон" />
                </div>
                <div class="politic">
                    <div class="checkbox">
                        <Icon style="font-size: 18px; color: var(--black-color)" icon="material-symbols:done" />
                    </div>
                    <text style="color: var(--orange-color)">Даю согласие на обработку моих персональных данных и соглашаюсь с политикой конфиденциальности</text>
                </div>
            </div>
            <div class="call-button">
                <text>Отправить</text>
            </div>
        </div>
    </div>
</div>
</template>
<script>
import { Icon } from '@iconify/vue';
export default {
	components: {
		Icon,
	},
};
</script>
<style scoped>
.container{
    width: 100vw;
    background-color: var(--black-color);
    color: var(--white-color);
    display: flex;
    flex-direction: column;
}


/*HEADER*/
.header{
    display: grid;
    grid-template-columns: 10% 65% 25%;
    grid-template-rows: 1;
    /* display: flex;
    flex-direction: row;
    justify-content: space-between; */
    padding-top: 16px;
    padding-bottom: 16px;
    width: 95vw;
    margin-left: auto;
    margin-right: auto;
    font-weight: var(--bold-font);
    font-size: 16px;
}

/*LOGO*/

/*ANCHORDS*/
.anchords{
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
}
.anchor{
    color: var(--white-color);
    text-decoration: none;
}
.anchor:hover{
    color: var(--orange-color);
}

/*NUMBER AND FEEDBACK*/
.number-feedback{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}
.number-icon{
    color: var(--white-color);
    display: flex;
    flex-direction: row;
    align-items: center;
    width: 50%;
}
.icon{
    font-size: 18px;
    margin-right: 3%;
}
.number-icon a{
    text-decoration: none;
    color: var(--white-color);
}
.feedback{
    background-color: var(--orange-color);
    padding: 8px 16px;
    border-radius: 16px;
    margin-left: 5%;
    cursor: pointer;
    
}
/*------*/


/*BODY*/
.body{
    width: 100vw;
    background-color: var(--gray-color);
}
/*----*/


/*FOOTER*/
.footer{
    width: 50vw;
    margin-left: auto;
    margin-right: auto;
    font-weight: var(--bold-font);
    display: flex;
    flex-direction: column;
    margin-top: 32px;
    text-align: center;
}
.footer-title{
    text-align: center;
    font-size: 1rem;
}
.footer-number{
    font-size: 36px;
    text-decoration: none;
    color: var(--white-color);
    margin-top: 16px;
    margin-bottom: 32px;
}

.inputs-politics{
    margin-top: 16px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 15vh;
}
.inputs{
    width: 45%;
    margin-left: auto;
    margin-right: auto;
    padding: 8px 16px;
    background-color: var(--white-color);
    border-radius: 6px;
    color: var(--black-color);
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    font-size: 28px;
}
.footer-icon{
    margin-right: 2%;
}
.inputs input{
    width: 80%;
    font-size: 16px;
    border: none;
}
.inputs input:focus{
    outline:none;
}

.politic{
    width: 48%;
    margin-left: auto;
    margin-right: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.checkbox{
    margin-right: 8px;
    background-color: var(--white-color);
    width: 18px;
    height: 18px;
    display: flex;
    align-items: center;
    border-radius: 2px;
    cursor: pointer;
}
.politic text{
    text-align: left;
    font-size: 14px;
}

.call-button{
    border: 4px solid #ff6600c0;
    width: 30%;
    margin-left: auto;
    margin-right: auto;
    padding: 16px 32px;
    font-size: 16px;
    border-radius: 32px;
    margin-top: 36px;
    margin-bottom: 36px;
}
/*------*/
</style>