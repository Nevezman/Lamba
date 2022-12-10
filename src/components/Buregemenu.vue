<template lang="">
    <div class="burger__menu">
        <div class="bureger__menu_list">
            <Push>
        <img class="menu__logo_image" src="@/assets/SVG/Logo.svg" alt="Эмблема Ламбы">
        <ul class="menu__burger">
            <li class="menu__items">
                    <a class="menu__link" href="#Info_scroll">О гонке</a>
                </li>
                <li class="menu__items">
                    <a class="menu__link" href="#track__scroll">Трек</a>
                </li>
                <li class="menu__items">
                    <a class="menu__link" href="#superEvo__scroll">Lamborghini Super trofeo</a>
                </li>
                <li class="menu__items">
                    <a class="menu__link" href="#blog__scroll">Новости</a>
                </li>
                <li class="menu__items">
                    <a class="menu__link" href="#buy-billets_scroll">Купить билеты</a>
                </li>
                <li class="menu__items">
                    <a class="menu__link" href="#watch_video">Смотреть онлайн</a>
                    
                </li>
                <li class="menu__items">
                    <a class="menu__link" href="#contacts__scroll">Контакты</a>
                </li>
            </ul>
        </Push>
            </div>
            
    </div>
</template>
<script>
import { Push} from 'vue3-burger-menu' 
export default {
    components: {
        Push
    }
}
</script>
<style scoped>
     
      .menu__logo_image {
        margin-left: 55px;
     }
     .menu__items {
        padding-bottom: 10px;
     }
     .menu__burger {
        display: block;
     }
    @media (min-width: 950px) {
        .burger__menu {
            display: none;
        }
    }
</style>