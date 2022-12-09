<template>
    <div class="superEvo__black">
        <div class="conteiner">
          <div class="superEVo__black_inner">
             <div class="superEvo__black_content">
               <h3 class="superEvo__black_title">СУПЕР ТРОФЕО ЭВО</h3>
                <div class="superEvo__black_wrapper">
                  <p class="superEvo__black_text">Новый Huracán Super Trofeo EVO достигает еще больших 
                высот, чем его прославленный предшественник, благодаря полностью переработанной аэродинамике. 
                Huracán Super Trofeo EVO является идеальной стартовой площадкой для всех водителей, 
                которые хотят начать карьеру в гонках класса GT.
                   </p>
                       <p class="superEvo__black_text">Huracán EVO — это эволюция самого успешного 
                Lamborghini с двигателем V10. В результате тонкой настройки и 
                усовершенствования существующих функций в сочетании с новыми конструктивными решениями, 
                повышающими производительность, автомобиль выделяется своей 
                способностью предугадывать и удовлетворять поведение, ожидания и желания водителя.
            </p>
            </div>
        </div>
        <img class="superEvo__black_img" src="../assets/Jpg/kindpngevo.png" alt="lamba">
        <dl class="superEvo__black_decr-list">
            <div>
            <dd>ПЕРЕМЕЩЕНИЕ</dd>
            <dt>5204 см³</dt>
            </div>
            <div>
            <dd>КРУТЯЩИЙ МОМЕНТ</dd>
            <dt>570 Нм при 6500 об/мин</dt>
            </div>
            <div>
            <dd>МОЩНОСТЬ (л.с.) / МОЩНОСТЬ (КВТ)</dd>
            <dt>620 л.с. при 8250 об/мин</dt>
            </div>
            <div>
            <dd>МАКС. СКОРОСТЬ</dd>
            <dt>325 км /ч</dt>
            </div>
            <div>
            <dd>0-100 КМ/Ч</dd>
            <dt>2,9 с</dt>
            </div>
        </dl>
          </div>
        </div>
    </div>
    <div class="superEvo__white">
        <div class="conteiner">
            <div class="superEVo__white_inner">
            <div class="superEvo__white_content">
                   <p class="superEvo__white_text">
                    Его неповторимый дизайн — это естественная 
                    эволюция культовых линий Huracán,
                     включающая новые сложные решения, поднимающие производительность и вызывающие эмоции на невиданный ранее уровень.
                    </p> 
                   <p class="superEvo__white_text">
                    Беспрецедентный обвес был разработан
                     инженерами отдела автоспорта Automobili Lamborghini в сотрудничестве 
                     с Dallara Engineering и Lamborghini Centro Stile. Последний также разработал стартовую ливрею 
                    для автомобиля в честь партнерства между Lamborghini Squadra Corse 
                    и Roger Dubuis, которое началось в 2018 году.
                </p> 
                   <p class="superEvo__white_text">Среди наиболее 
                    очевидных изменений в обвесе Lamborghini Huracan Super 
                    Trofeo EVO — задний спойлер на заднем капоте и верхний 
                    воздухозаборник, которые делают его мгновенно узнаваемым 
                    для зрителей.</p> 

            </div>
            <div class="superEvo__white_video">
                <a class="superEvo__white_video-arrow" href="#">
                    <img src="../assets/SVG/arcticons_youtube-studio.svg" alt="youtube">
                    <span>смотреть онлайн</span>
                </a>
            </div>
        </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
.superEvo__black {
    background-color: #363636;
    
    
}
.superEvo__black_content {
    display: flex;
    justify-content: space-between;
    padding-top: 100px;
    
}
.superEvo__black_title{
    color: #fff;
}
.superEvo__black_wrapper{
    color: #fff;
    flex-basis: 437px;
}
.superEvo__black_text {
    margin-bottom: 30px;
}
.superEvo__black_decr-list {
display: flex;
gap: 65px;
color: #fff;
padding-bottom: 50px;
}
.superEvo__black_img {
    display: block;
    margin: 200px auto 60px auto;
    align-items: center;
    position: relative;
    z-index: 8;
}
.superEvo__white_content {
    padding-top: 125px;
}
.superEvo__white_text {
    margin-bottom: 30px;
}
.superEvo__white_text:first-child {
max-width: 285px;
}
.superEvo__white_text:nth-child(2) {
    max-width: 437px;
}
.superEvo__white_text:nth-child(3) {
    max-width: 590px;
}
.superEvo__white_video {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    height: 264px;
    margin: 100px auto;
    background-image: url(../assets/Jpg/Polygon6.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    
}
.superEvo__white_video-arrow span{
display: block;
color: #fff;
}
.superEVo__black_inner {
    position: relative;
}
.superEVo__black_inner::before {
    content: "";
    background-image: url(../assets/SVG/Polygon1.svg);
    width: 185px;
    height: 213px;
    position: absolute;
    left: -145px;
    top: 341px;
}
.superEVo__black_inner::after {
    content: "";
    background-image: url(../assets/SVG/Polygon2.svg);
    width: 498px;
    height: 572px;
    position: absolute;
    left: -47px;
    top: 426px;
    z-index: 1;
}
.superEVo__white_inner {
    position: relative;
}
.superEVo__white_inner::before {
    content: "";
    background-image: url(../assets/Jpg/Group3.png);
    width: 274px;
    height: 257px;
    position: absolute;
    left: 354px;
    top: -23px; 
}
.superEVo__white_inner::after {
    content: "";
    background-image: url(../assets/Jpg/Group4.png);
    width: 324px;
    height: 311px;
    position: absolute;
    left: 591px;
    top: 120px;

}
@media (max-width: 950px){
    .superEVo__white_inner::after {
        display: none;
    }
    .superEvo__black_decr-list {
        gap: 20px;
    }
    .superEvo__white_video {
        background-size: 100%;
    }
}


</style>