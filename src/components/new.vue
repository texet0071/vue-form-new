<template>
    <div class="container">

        <form class="card">

            <h1>Регистрация</h1>

            <h2>Уже есть аккаунт?<a href="#"> войти</a> </h2>

            <div class="from-label">
                <label class="from-label_label" for="name">Имя</label>
                <input class="from-label_input"  type="text" id="name" placeholder="Введите Ваше имя">
            </div>

            <div class="from-label">
                <label class="from-label_label" for="email">Email</label>
                <input class="from-label_input" type="email" id="email" placeholder="Введите ваш email">
            </div>

            <div class="from-label">
                <label class="from-label_label" for="phone">Номер телефона</label>
                <input class="from-label_input" type="phone" id="phone" placeholder="Введите номер телефона">
            </div>

            <div class="from-label">
                <label for="language">Язык</label>
                <select id="language">
                    <option value="rus">Русский</option>
                    <option value="eng">Английский</option>
                    <option value="China">Китайский</option>
                    <option value="spanish">Испанский</option>
                </select>
            </div>


            <div class="content-rule">
                <h2 class="rule">Принимаю <a href="#">условия</a> использования</h2>
            </div>

            <div class="reg">
                <button class="btn" >Зарегистрироваться</button>
            </div>

        </form>

    </div>

</template>

<script>
    export default {

    }
</script>

<style scoped>

    a {
        text-decoration: none;
        height: 22px;
        font-style: normal;
        font-weight: normal;
        font-size: 16px;
        line-height: 22px;
        color: #0880AE;
    }


    .container {
        margin: 0 auto;
        max-width: 1000px;
    }

    .card {
        width: 460px;
        padding: 16px;
        border-radius: 24px;
        box-shadow: 0px 12px 24px rgba(44, 39, 56, 0.02);
        background: #fff;
    }

    h1  {
        margin-left: 30px;
        font-size: 34px;
        color: #2C2738;
        margin-bottom: 9px;
    }

    h2{
        margin-left: 30px;
        margin-bottom: 57px;
        font-size: 16px;
        line-height: 22px;
        color: #2C2738;
    }

    .from-label {
        margin-top: 57px;
        position: relative;

    }
    .from-label_input {

    }

    .from-label_label {
        margin-bottom: auto;
    }

    input,
    select
    {
        margin-left: 30px;
        width: 400px;
        height: 52px;
        padding: 0 16px;
        position: absolute;
        left: 0px;
        right: 0px;
        top: 0px;
        bottom: 0px;
        background: #FFFFFF;
        border: 1px solid #DBE2EA;
        box-sizing: border-box;
        box-shadow: 0px 4px 8px rgba(44, 39, 56, 0.04);
        border-radius: 6px;
    }



    select{
        background: #FFFFFF;
        border: 2px solid #0880AE;
        box-sizing: border-box;
        box-shadow: 0px 4px 8px rgba(44, 39, 56, 0.04);
        border-radius: 6px;
    }


    input::-webkit-input-placeholder {
        position: absolute;
        width: 287px;
        height: 21px;
        left: 16px;
        top: 16px;
        font-style: normal;
        font-weight: normal;
        font-size: 16px;
        line-height: 21px;
        color: #7C9CBF;
    }

    .content-rule {
        display: flex;
        justify-content: center;
    }

    .rule {
        padding-top: 36px;
        margin: 35px 124px 42px 66px ;
        text-align: center;
    }



    .reg {
        text-align: center;

    }

    .btn {
        font-weight: 500;
        font-size: 16px;
        line-height: 21px;
        text-align: center;
        padding: 18px 121px 17.57px 121px;
        margin-bottom: 41px;
        background: #DBE2EA;
        color: #B1B5BF;
        box-shadow: 0px 2px 4px rgba(44, 39, 56, 0.08), 0px 4px 8px rgba(44, 39, 56, 0.08);
        border-radius: 6px ;
        border: 1px solid #DBE2EA;
    }

    .check {
        display: block;
        position: absolute;
    }

</style>