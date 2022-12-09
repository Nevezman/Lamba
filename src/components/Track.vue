<template>
    <div class="track__content">
        <div class="track__info">
            <h3 class="track__title">ТРЕК ПОРТИМАО</h3>
            <p class="track__text">Autodromo Internacional do Algarve находится в одноименном регионе 
                на юге Португалии, недалеко от города Портиман. Открытый в октябре 
                2008 года автогоночный комплекс является одним из самых современных в Европе, 
                раскинувшись на площади около 300 гектаров среди холмов, окружающих 
                португальский город, а длина самой трассы составляет 4684 метра.</p>

        </div>
        <div class="track__maps">
            <img class="track_img" src="../assets/Jpg/Track.png">
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
  .track__content {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    
    
  }
  .track__title {
    padding-top: 50px;
    padding-bottom: 30px;
   
  }
  .track__info{
    max-width: 434px;
  }
  .track__maps {
    align-self: flex-end;
    padding-bottom: 55px;
  }
  @media (max-width: 810px) {
    .track_img {
      max-width: 100%;
    }
  }
</style>