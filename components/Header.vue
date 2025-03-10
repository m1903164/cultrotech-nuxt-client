<template>
    <header class="header">
        <div class="header__container">
            <nav class="header__menu">
                <ul class="header__menu__list">
                    <li>О комании</li>
                    <li>Новости</li>
                    <li>Галерея</li>
                    <li>Доставка и опалата</li>
                    <li>Контакты</li>
                    <li>Парнеры</li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<style scoped lang="scss">
.header {
    background-color: #150C07;
    color: white;
    &__container {
        max-width: 1170px;
        display: flex;
        align-items: center;
        margin-left: auto;
        margin-right: auto;
    }

    &__menu {
        &__list {
            display: flex;
            list-style: none;
            gap: 40px;
        }
    }
}
</style>