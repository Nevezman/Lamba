<template>
    <div class="blog__slider">
      <h3 class="blog__slider_title">БЛОГ</h3>
      <div class="blog_swiper">
    <swiper
    :modules="modules"
    :slides-per-view="2"
    :space-between="20"
    :navigation="{nextEl:'.swipper__arrow-next',prevEl:'.swipper__arrow-prev'}"
    @swiper="onSwiper"
    @slideChange="onSlideChange"
    :loop="true"
  > 
  
    <swiper-slide>
      <img class="slide_img" src="../assets/Jpg/Rectangle18.jpg" alt="winners">
      <h4 class="slide_title">НЕЛЬСОН ПИКЕ СТАЛ ПОБЕДИТЕЛЕМ ГРАНД-ФИНАЛА В ПОРТИМАНЕ</h4>
      <p class="slide_text"
      :class="isReadOne ? 'large_one' : ''">
      Нельсон Пике-младший из Ansa Motorsports обеспечил возвращение титула Lamborghini Super Trofeo Grand Finals 
        в Северную Америку впервые с 2017 года после победы и второе место в паре 50-минутных гонок на Autodromo Nacionale do Algarve в 
        Портимане.Между тем, титул Pro-Am был подорван, поскольку Брайан Ортис и Себастьян Карасо из Precision Performance Motorsports 
        стали первым полностью пуэрто-риканским составом, выигравшим Гранд-финал, сделав это драматично после того, как сравнялись по очкам 
        с Брайсон Лью и Джон Дубетс.Анджей Левандовски из VS Racing одержал свою вторую победу в Гранд-финале, добавив титул Am к своему 
        успеху Pro-Am, которого он добился с Каролем Башем в 2019 году, в то время как бельгийские братья и сестры Бенуа и Франсуа Семулен 
        завоевали корону Кубка Lamborghini для Semspeed.Победитель Гранд-финала в категории Pro Нельсон Пике-младший (#130 Ansa Motorsports) 
        сказал: « Выиграть титул удивительно, но это определенно была непростая гонка. Я попросил своего инженера еще немного стравить 
        давление в шинах на пит-стопе, но этого оказалось недостаточно, поэтому на втором отрезке у меня были проблемы. Я видел, 
        как приближается Дэнни [Формал] [Wayne Taylor Racing] и немного волновался, потому что он мог что-то попробовать, потому что ему было нечего терять. 
        Я знал, что этой секунды было бы достаточно, чтобы выиграть титул, но всегда хочется сделать это, выиграв гонку». </p>
        <label class="slide_lable"><input type="checkbox" v-model="isReadOne" class="slide_link">Читать подробнее...</label>
    
    </swiper-slide>
    <swiper-slide>
      <img class="slide_img" src="../assets/Jpg/autoslider.jpg" alt="lamba">
      <h4 class="slide_title">ГРАНД ФИНАЛ. ДЕНЬ 1</h4>
      <p class="slide_text" 
      :class="isReadTwo ? 'large_two' : ''">
      Утренний дождь означал, что мокрая гонка была объявлена ​​до старта,
         и перед большинством экипажей стоял выбор: использовать слики или мокрые шины. Большинство у
         частников предпочли мокрую трассу, но поулист Спинелли начал гонку на сликах и сразу же поплатился 
         за это. Huracan № 61 опустился вниз, заняв всего 28-е место, поскольку Бондуэль опередил бегунов Pro-Am 
         Кароля Баша (Micanek Motorsport) и Льюиса Уильямсона (Oregon Team).Вскоре Уильямсон опередил Баса, заняв 
         первое место в Pro-Am и заняв второе место в общем зачете, но гонщик команды Орегона не был доволен тем, 
         что остался на этом месте, поскольку он отнимал у Бондюэля часть времени впереди. Вскоре Уильямсон оказался 
         позади Бондюэля и сделал решающий рывок на восьмом повороте, чтобы захватить лидерство на седьмом круге. Таков 
         был темп машины под номером 27, Уильямсон построил трехсекундный отрыв и удерживал лидерство до пит-стопов.Бондуэль, 
         который боролся с высоким давлением в шинах на первом отрезке, перешел на слики на пит-стопах и снова вышел в лидеры 
         после того, как обогнал Бромека Форманека, в то время как автомобиль Target Racing из Milan Teekens оспаривал третье 
         место с машиной Iron Dames. Дориан Пин. Пин № 83 поднялся на второе место перед Тикенсом после остановок, но в конце 
         гонки попал под давление со стороны Тикенса. Teekens обогнал Пина на последних кругах и финишировал вторым после вращения 
         Форманека за два круга до финиша, в то время как Пин также развернулся на последнем круге и занял пятое место в общем зачете.
         Получив прибыль от вращения Форманека, Сиглия и Уильямсон финишировали третьими в общем зачете и первыми в Pro-Am, завоевав 
         титул на гонку раньше. Бенуа Семулен и Франсуа Семулен выиграли в классе Lamborghini Cup, опередив Ван дер Хорста и Ханса Фабри,
          а Левандовски одержал победу в классе Am. </p>
          <label class="slide_lable"><input type="checkbox" v-model="isReadTwo" class="slide_link">Читать подробнее...</label>
        
    </swiper-slide>
   

  </swiper> 
  <div class="swipper__arrows">
      <div class="swipper__arrow-prev">
      <img class="swipper__arrow-prev_icons" src="../assets/SVG/arrowleft.svg" alt="arrow">
      </div>
    <div class="swipper__arrow-next">
      <img class="swipper__arrow-next_icons" src="../assets/SVG/arrowright.svg" alt="arrow">
    </div>
    </div>
    </div>
    </div>

    <div class="blog__winer">
      <div class="blog__winer_info">
        
        <dl>
          <dd class="blog__winer_turName">Чемпион Am</dd>
          <dt class="blog__winer_Name">Анджей Левандовски </dt>
        </dl>
        <p class="blog__winer_text">«Я очень доволен титулом, моей второй победой в Am и четвертой в Super Trofeo, 
          мне очень приятно делать это в этом году, 
          потому что уровень соревнований очень высок. Должен сказать, сегодня было довольно легко, 
          так как я все время контролировал ситуацию».</p>
         
         
        <dl class="blog__winer_inner">
          <dd class="blog__winer_turName">Обладатель кубка Lamborghini</dd>
          <dt class="blog__winer_Name">Жерар ван дер Хорст </dt>
        </dl>
        <p class="blog__winer_text expand">«Я очень доволен титулом, моей второй победой в Am и четвертой в 
          Super Trofeo, мне очень приятно делать это в этом году, потому что уровень соревнований 
          очень высок. Должен Обладатель кубка Lamborghini  добавил: «Здорово выиграть титул, спустя 
          четыре года после последнего, а за это время произошло так много всего. Из-за COVID-19, а з
          атем моей тяжелой аварии в Барселоне я не мог так много ездить в последние годы, поэтому я очень 
          доволен своим возвращением. Сегодня утром была тяжелая гонка, но я справился».
           сказать, сегодня было довольно легко, так как я все время контролировал ситуацию».</p>
         

      </div>
      <div class="blog__winer_foto">
        <img class="blog__winer_img" src="../assets/Jpg/finner.jpg">
      </div>
    </div>
</template>
<script>

import { Navigation, } from 'swiper';


import { Swiper, SwiperSlide } from 'swiper/vue';

import 'swiper/css';
import 'swiper/css/navigation';

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    const onSwiper = (swiper) => {
      console.log(swiper);
    };
    const onSlideChange = () => {
      console.log('slide change');
    };
    return {
      onSwiper,
      onSlideChange,
      modules: [Navigation],
      
    };
  },
  data () {
    return {
      isReadOne : false,
      isReadTwo : false
    }

    },

 
};
</script>
<style>
.blog__slider_title {
  margin-bottom: 30px;
}

.swipper__arrows {
  display: flex;
    gap: 20px;
   position: absolute;
   top: 0px;
   left: 408px;
  }
  .slide_title {
font-style: normal;
font-size: 20px;
text-transform: uppercase;
font-weight: 400;
margin-bottom: 10px;
min-height: 46px;
  }
  .slide_img{
    margin-bottom: 20px;
  }
  .slide_text {
    margin-bottom: 10px;
    height: 85px; 
    overflow: hidden;
  }
  .slide_link {
    display: none;
   
  }
  .blog_swiper {
    position: relative;
    padding-top: 50px;
    
  }
  
  .large_one {
    height: 350px;
    transition: 1s;
  }
  .large_two {
    height: 450px;
    transition: 1s;
  }
  .slide_lable {
    cursor: pointer;
    color: #363636;
    font-size: 12px;
    
    
  }
  .blog__winer {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-top: 100px;
    
  }
  .blog__winer_turName {
    color: #9F6B08;
    font-size: 12px;
    
  }
  .blog__winer_Name {
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    padding-bottom: 10px;
  }
  .blog__winer_text {
    font-style: italic;
    max-width: 434px;
    margin-bottom: 30px;
  }
  .expand {
    max-height: 69px;
    overflow: hidden;
    transition: 1s;
  }
  .expand:hover {
    max-height: 150px;

  }
  @media (max-width: 950px){

.swiper-slide img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
  }
  .swipper__arrows {
   top: 0px;
   left: 321px;
  }

    }
  
  


 
  
</style>