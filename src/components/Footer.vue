<template>
    <div class="footer">
    <h3 class="footer__title" id="contacts__scroll">Контакты</h3>
    <div class="footer__content_up">
        <div class="footer__content_info">
          <ul>
            <li>
                <dl class="footer__content_position">
                     <dt class="footer__content_subtitle">ОБЩИЕ</dt>
                     <dd class="footer__content_text"><a href="tel:+351282405600">+(351) 282 405 600</a></dd>
                     <dd class="footer__content_text"><a href="tel:+351282405697">+(351) 282 405 697</a></dd>
                     <dd class="footer__content_text"><a href="mailto:info@autodromodoalgarve.com">info@autodromodoalgarve.com</a> </dd>
                </dl>
            </li>
            <li>
                <dl class="footer__content_position">
                     <dt class="footer__content_subtitle" id="buy-billets_scroll">БИЛЕТЫ</dt>
                     <dd class="footer__content_text"><a href="tel:+351282405600">+(351) 282 405 600</a></dd>
                     <dd class="footer__content_text"><a href="mailto:tickets@autodromodoalgarve.com">tickets@autodromodoalgarve.com</a> </dd>
                </dl>
            </li>
            <li>
                <ul class="footer__content_social-list">
                    <li><a href=#><img src="../assets/SVG/YOUTUBE.svg" alt="youtube"></a></li>
                    <li><a href=#><img src="../assets/SVG/INST.svg" alt="instogram"></a></li>
                    <li><a href=#><img src="../assets/SVG/FACEBOOK.svg" alt="facrbook"></a></li>
                </ul>
            </li>
          </ul>
        </div>
        <div class="footer__content_map">
            <dl>
                <dt class="footer__content_subtitle">АДРЕС</dt>
                <dd class="footer__content_text">Sitio do Escampadinho, Mexilhoeira Grande, 8500-148 Portimao, Portugal </dd>
            </dl>
            <GoogleMap api-key="" style="width: 454зч; height: 253px" :center="center" :zoom="14" :options="options">
    
             <Marker :options="{ position: center }" />
  </GoogleMap>
        </div>
    </div>
    <div class="footer__content_down">

    </div>
    </div>
</template>
<script>

  import { defineComponent } from "vue";
import { GoogleMap, Marker } from "vue3-google-map";

export default defineComponent({
  components: { GoogleMap, Marker },
  setup() {
    const center = { lat: 37.23162773154195, lng: -8.628272372789242 };
   
       
    return { center
}
  }
});

    
 
</script>
<style>
.footer__content_up {
    display: flex;
    justify-content: space-between;
}
 .footer__content_info ul {
    list-style-type: none;
 }   
 .footer__title{
    margin-bottom: 50px;
 }
 .footer__content_subtitle{
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    padding-bottom: 20px;
 }
 .footer__content_text{
    font-style: normal;
    font-weight: 400;
    font-size: 15.5307px;
    padding-bottom: 10px;
 }
  .footer__content_position{
    padding-bottom: 50px;
  }
  .footer__content_social-list {
    display: flex;
    gap: 20px;
  }
  @media (max-width: 760px){
    .footer__content_up {
    display: block;
    }
    .footer__content_social-list {
        margin-bottom: 30px;
    }

  }


</style>