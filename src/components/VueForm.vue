<template>
    <div class="container">
        <form class="card">
            <h1>Регистрация</h1>
            <div class="form-card_reg">
                <h2>Уже есть аккаунт?<a href="#">войти</a> </h2>

            </div>
            <div class="from-label">
                <label for="name">Имя</label>
                <input type="text" id="name" placeholder="Введите Ваше имя">
            </div>
            <div class="from-label">
                <label for="email">email</label>
                <input type="email" id="email" placeholder="Введите ваш email">
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
            <h2 class="rule">Принимаю <a href="#">условия</a> использования</h2>
            <button class="btn" @click="">Зарегистрироваться</button>
        </form>
    </div>
</template>

<script>
    export default {

    }
</script>

<style scoped>

</style>