<template >
    <div class="conteiner">
        <nav class="menu">
            <ul class="menu__list menu__left">
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
            </ul>
            <img class="menu__logo_image" src="@/assets/SVG/Logo.svg" alt="Эмблема Ламбы">
            <ul class="menu__list menu__right">
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

        </nav>
        </div>
    
    
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .conteiner {
    max-width: 1220px;
    padding: 0 10px;
    margin: 0 auto;
  }
    .menu {
        display: flex;
        justify-content: space-between;
    }
    .menu__list {
        display: flex;
        gap: 40px;
        padding-top: 25px;
    }

    .menu__link{
        color: #363636;
        font-size: 16px;
    }
    .menu__right {
        padding-right: 90px;

    }
    .menu__left {
        padding-left: 25px;
    }
    @media (max-width:1050px) {
        .menu__list {
            gap: 28px;
        }
        .menu__right {
        padding-right: 80px;
        }
        .conteiner{
            max-width: none;
        }
    }
    @media (max-width: 950px) {
        .menu {
            display: none;
        }

    }
        

        

    
</style>