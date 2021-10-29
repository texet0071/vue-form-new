<template>
    <div class="card">
        <form class="form form-border">

            <h1>Регистрация</h1>
            <p>Уже есть аккаунт? <a href="#">Войти</a></p>

            <div class="account-info">

                <div class="info-name">
                    <label for="name">Имя</label>
                    <input type="name" id="name" placeholder="Введите Ваше имя">
                </div>

                <div class="info-email">
                    <label for="Email">Еmail</label>
                    <input type="email" id="email" placeholder="Введите ваш email">
                </div>

                <div class="info-phone">
                    <label for="Phone">Номер телефона</label>
                    <input type="Phone" id="Phone" placeholder="Введите номер телефона">
                </div>


                <label for="laung">Язык</label>
                <select name="laung" id="laung">
                    <option style="display: none">Язык</option>
                    <option value="rus">Русский</option>
                    <option value="eng">Английский</option>
                    <option value="china">Китайский</option>
                    <option value="spanish">Испанский</option>
                </select>

            </div>

            <div class="ruls">
                <input type="checkbox" class="ruls-in">Принимаю <a href="#">условия </a> использования
            </div>

            <div class="btn-reg">
                <button class="btn">Зарегистрироваться</button>
            </div>

        </form>
    </div>
</template>

<script>
    export default {

    }
</script>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:wght@300&display=swap');

    a {
        text-decoration: none;
        color:#0880AE ;
    }


    .card {
        margin: 0 auto;
        max-width: 45%;
    }

    form {
        overflow: hidden;
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

    p{
        margin-left: 30px;
        margin-bottom: -47px;
        font-size: 16px;
        line-height: 22px;
        color: #2C2738;
    }

    .form-border {
        border: 0;
        margin: 0;
        padding: 0;
    }

    input::-webkit-input-placeholder {
        width: 287px;
        height: 21px;
        font-size: 16px;
        line-height: 21px;
        color: #7C9CBF;
    }

    .account-info {
        padding: 85px 30px 33px 30px;
    }

   .account-info input,select {
        display: block;
        width: 400px;
        height: 52px;
        background: #FFFFFF;
        border: 1px solid #DBE2EA;
        box-sizing: border-box;
        box-shadow: 0px 4px 8px rgba(44, 39, 56, 0.04);
        border-radius: 6px;
        margin: 0;
    }


    .account-info label {
        color: #395870;
        display: block;
        padding-bottom: 7px;
        font-weight: bold;
        margin-bottom: 20px;

    }
    .account-info input{
        background: #FFFFFF;
        border: 1px solid #DBE2EA;
        box-sizing: border-box;
        box-shadow: 0px 4px 8px rgba(44, 39, 56, 0.04);
        border-radius: 6px;
        color: #636466;
        padding: 16px;
        margin-top: -6px;
        width: 100%;
    }

    .info-name{
        padding-bottom: 33px;
    }

    .info-email {
        padding-bottom: 34px;
    }

    .info-phone {
        padding-bottom: 34px;
    }



    .ruls {
        padding-left: 30px;
    }


    .btn-reg {
        padding-left: 30px;
        margin-top: 42px;
    }

    .btn {
        font-weight: 500;
        font-size: 16px;
        line-height: 21px;
        text-align: center;
        padding: 18px 121px 17px 121px;
        margin-bottom: 41px;
        background: #DBE2EA;
        color: #B1B5BF;
        box-shadow: 0px 2px 4px rgba(44, 39, 56, 0.08), 0px 4px 8px rgba(44, 39, 56, 0.08);
        border-radius: 6px ;
        border: 1px solid #DBE2EA;
    }





</style>