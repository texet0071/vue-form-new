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


                <div class="box">
                    <label for="laung">Язык</label>
                    <select name="laung" id="laung">
                        <option style="display: none">Язык</option>
                        <option value="rus">Русский</option>
                        <option value="eng">Английский</option>
                        <option value="china">Китайский</option>
                        <option value="spanish">Испанский</option>
                    </select>
                </div>

            </div>

            <div class="checkbox">
                <input type="checkbox" class="custom-checkbox" id="check" name="check">
                <label for="check">Принимаю <a href="#">условия </a> использования</label>
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
        padding: 10px;
        margin: 0 auto;
        max-width: 30%;
    }

    form {
        overflow: hidden;
        width: 460px;
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

   .account-info input {
        display: block;
        margin: 0;
    }

   .account-info select {
       display: block;
       width: 400px;
       height: 52px;
       background: #FFFFFF;
       border: 2px solid #0880AE;
       box-sizing: border-box;
       box-shadow: 0px 4px 8px rgba(44, 39, 56, 0.04);
       border-radius: 6px;
   }

    .account-info label {
        color: #395870;
        display: block;
        padding-bottom:  7px;
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
        width: 100%;
    }

    .custom-checkbox {
        position: absolute;
        z-index: -1;
        opacity: 0;
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

    .custom-checkbox+label {
        display: inline-flex;
        align-items: center;
        user-select: none;
    }
    .custom-checkbox+label::before {
        content: '';
        display: inline-block;
        width: 28px;
        height: 28px;
        flex-shrink: 0;
        flex-grow: 0;
        border: 1px solid #DBE2EA;
        box-sizing: border-box;
        box-shadow: 0px 4px 8px rgba(44, 39, 56, 0.04);
        border-radius: 4px;
        margin-right: 8px;
    }

    .custom-checkbox:checked+label::after {
        border-color: #0b76ef;
        background-color: #0b76ef;
        background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 8 8'%3e%3cpath fill='%23fff' d='M6.564.75l-3.59 3.612-1.538-1.55L0 4.26 2.974 7.25 8 2.193z'/%3e%3c/svg%3e");
    }

    .custom-checkbox:not(:disabled):not(:checked)+label:hover::before {
        border-color: #b3d7ff;
    }

    .custom-checkbox:not(:disabled):active+label::before {
        background-color: #b3d7ff;
        border-color: #b3d7ff;
    }

    .custom-checkbox:focus+label::before {
        box-shadow: 0px 4px 8px rgba(44, 39, 56, 0.04);
    }

    .custom-checkbox:focus:not(:checked)+label::before {
        border-color: #80bdff;
    }

    .custom-checkbox:disabled+label::before {
        background-color: #e9ecef;
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


    .checkbox {
        padding-left: 30px;
    }

    .checkbox a {
        padding: 0 3px 0 3px;
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