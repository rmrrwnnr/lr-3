<script setup>

</script>

<template>
    <header>
        <div class="container">
            <nav class="navigation">
                <img class="navigation-logo" src="/logo.svg" alt="">
                <ul class="navigation__list">
                    <li class="navigation__list-item">
                        <a href="#" class="navigation__list-item-link">
                            Возможности
                        </a>
                    </li>
                    <li class="navigation__list-item">
                        <a href="#" class="navigation__list-item-link">
                            Как это работает?
                        </a>
                    </li>
                </ul>
            </nav>
        </div>
        <div class="navigatiom-mob">
            <div class="container">
                <div class="adaptiv" id="">
                    <img class="logo-adaptiv" src="/logo-adapt.png" alt="">
                    <div class="shadowAll" id="show__all"></div>
                    <button class="header__burger-btn" id="burger">
                        <span></span>
                        <span></span>
                        <span></span>
                    </button>
                    <nav class="menu" id="menu">
                        <ul class="menu__list">
                            <li class="menu__item">
                                <a href="#opportunities" class="menu__link">
                                    Возможности
                                </a>
                            </li>
                            <li class="menu__item">
                                <a href="#materials" class="menu__link">
                                    Как это работает?
                                </a>
                            </li>
                        </ul>
                        <ul class="menu__bottom">
                            <li class="menu__item-bottom">
                                <a href="#" class="menu__link-bottom">
                                    г Сургут, ул Базовая, д. 34, офис 10<br>
                                    ОГРН 1238600001200<br>
                                    ИНН 8602309464
                                </a>
                            </li>
                            <li class="menu__item-bottom">
                                <a href="#" class="menu__link-bottom">
                                    ООО Дотсолюшн © 2023
                                </a>
                            </li>
                        </ul>
                    </nav>
                </div>
            </div>
        </div>
    </header>
</template>

<style scoped>

</style>