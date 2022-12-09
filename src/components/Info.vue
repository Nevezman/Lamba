<template>
    <div class="Info__part world-final" id="Info_scroll">
        <h3 class="Info__title">СУПЕР ТРОФЕО МИРОВОЙ ФИНАЛ</h3>
        <div class="Info__content">
            <p class="Info__text_normal">Мировой финал Lamborghini завершает каждый 
            сезон Super Trofeo с 2013 года. 
            Каждый год гонщики всех континентальных чемпионатов 
            отправляются на разные трассы и принимают участие в двух 50-минутных 
            спринтерских гонках, где определяется победитель в общем зачете. 
            как чемпион мира Lamborghini. 
            Мировой финал Lamborghini — это не только 
            крупнейший гоночный уик-энд года, н
            о и настоящий 
            фестиваль автоспорта, 
            который привлекает поклонников со всего мира.
        </p>
        <b class="Info__text_bold">Парад владельцев, превью и развлечения в паддоке для болельщиков — 
           это лишь некоторые из мероприятий, организованных в рамках мероприятия.
            </b>
        </div>
        <img class="Info__img" src="../assets/Jpg/finalstart.jpg" alt="start lamba racing">
    </div>

    <div class="Info__part team">
       
        <div class="Info__content" >
            <div class="Info__text-team">
                <h3 class="Info__title">КОМАНДЫ СУПЕР ТРОФЕО</h3>
            <p class="Info__text-team-box">Все автомобили, которые участвуют в чемпионатах Lamborghini 
                Super Trofeo, управляются 
                частными командами, которые используют свой 
                опыт для тонкой настройки их для водителей. 
                Для каждого континентального чемпионата Lamborghini Super 
                Trofeo существуют рейтинги пилотов и команд.
            </p>
            <p class="Info__text-team-box">Пилоты и команды, участвующие в континентальной серии, каждый год 
                соревнуются друг с другом в Гранд Финале Lamborghini, мероприятии,
                 которое завершает спортивный сезон Super Trofeo. Две квалификационные 
                 сессии и две гонки определяют чемпионов мира серии. 
                Каждый год Гранд-финал проводится на разных трассах, и в прошлых 
                выпусках он уже затрагивал европейский, азиатский и американский континенты.</p>
            </div>
            <div class="Info__picture">
            <img class="Info__img" src="../assets/Jpg/teamfoto.jpg" alt="lamba racing">
            </div>
        </div>
    </div>
    <div class="Info__part calendar">
        <div class="Info__content">
        <div class="info_calendar_text">
            <h3 class="Info__title">календарь сезона Super Trofeo Europe 2022 года</h3>
            <p>14 в истории серии GT, посвященный автомобилям Lamborghini Huracan Super Trofeo Evo.
                 Шесть этапов, в общей сложности 12 гонок и 
                600 минут соревнований будут разыграны на некоторых из самых престижных трасс Европы.</p>
        </div>
         <table class="Info__calendar_table">
            <tr>
                <td>Этап 1: </td>
                <td>Имола (Италия)</td>
                <td>1-3 апреля</td>
            </tr>
            <tr>
                <td>Этап 2:</td>
                <td>Ле-Кастелле (Франция)</td>
                <td>3–5 июня</td>
            </tr>
            <tr>
                <td>Этап 3:</td>
                <td>Мизано (Италия)</td>
                <td>1–3 июля</td>
            </tr>
            <tr>
                <td>Этап 4:</td>
                <td>Спа-Франкоршам (Бельгия)</td>
                <td>29–30 июля</td>
            </tr>
            <tr>
                <td>Этап 5:</td>
                <td>Барселона (Испания)</td>
                <td>30 сентября–2 октября</td>
            </tr>
            <tr>
                <td>Этап 6:</td>
                <td>Портимао (Португалия)</td>
                <td>3-4 ноября</td>
            </tr>
            <tr>
                <td>Гранд-финал 2022 :</td>
                <td>Портимао (Португалия)</td>
                <td>5-6 ноября</td>
            </tr>
         </table>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
.Info__part {
    margin-top: 100px;
}
 .Info__title {
    padding-bottom: 30px;
 }
 .Info__content {
    display: flex;
    justify-content: space-between;
    gap: 20px;
    margin-bottom: 30px;
 }  
 .Info__text_normal {
    flex-basis: 50%;
  }
  .Info__text_bold {
    flex-basis: 50%;
  }
  .Info__text-team{
    padding-right: 80px;
  }
  .Info__text-team-box{
    max-width: 352px;
    padding-bottom: 30px;
  }
  .Info__img {
    object-fit: cover;
  }
  .info_calendar_text {
    flex-basis: 377px;
  }
  .Info__calendar_table {
    flex-basis: 450px;
    border-bottom: 1px solid #040404;
    position: relative;
    top: 20px;
  }
  .Info__calendar_table td{
    padding-bottom: 20px;

  }
  .Info__calendar_table::before{
    top: -20px;
    content: "";
    border-top: 1px solid #040404;
    position: absolute;
    width: 100%;

  }
  @media (max-width: 960px) {
    .Info__img { 
      width: 100%;
    }
  }
  
</style>