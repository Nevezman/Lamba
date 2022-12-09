<template>
    <div class="promo__inner">
        <h1 class="promo__title">LAMBORGHINI SUPER TROFEO</h1>
        <h2 class="promo__subtitle">
            Гранд-финал 2022
            <span>3-6 ноября </span>
        </h2>
        <p class="promo__text">автодром Портимао,Португалия</p>
        <a class="promo__arrow" href="#Info_scroll"><img src="../assets/SVG/Arrow.svg"></a>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
@font-face {
	font-family: 'Impact';
	src: url('../assets/fonts/impact.eot'); /* IE 9 Compatibility Mode */
	src: url('../assets/fonts/impact.eot?#iefix') format('embedded-opentype'), /* IE < 9 */
		url('../assets/fonts/impact.woff2') format('woff2'), /* Super Modern Browsers */
		url('../assets/fonts/impact.woff') format('woff'), /* Firefox >= 3.6, any other modern browser */
		url('../assets/fonts/impact.ttf') format('truetype'), /* Safari, Android, iOS */
		url('../assets/fonts/impact.svg#impact') format('svg'); /* Chrome < 4, Legacy iOS */
}
.promo__inner {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    padding-top: 100px;
}
   .promo__title {
    font-family: "Impact", sans-serif;
    font-style: normal;
    font-size: 76px;
    font-weight: 400;
    letter-spacing: 0.02em;
    margin-bottom: 10px;
    
   }
   .promo__subtitle {
    font-family: "Impact", sans-serif;
    font-style: normal;
    font-weight: 400;
    font-size: 48px;
    border-bottom: 1px solid #040404;
    margin-bottom: 10px;
    align-self: center;
   }
   .promo__subtitle span {
    display: block;
    color: #9F6B08;
    font-size: 34px;
    padding: 10px 0;
   }
   .promo__text {
    color: #363636;
    font-size: 16px;
   }
   .promo__arrow {
    align-self: center;
    margin-top: auto;
    margin-bottom: 30px;
   }
   @media (max-width: 950px) {
    .promo__title {
        font-size: 60px;
    }
   }

</style>