<script setup>
import Swiper from 'swiper';
import { onMounted } from 'vue';
import { Pagination } from 'swiper/modules';

onMounted(() => {
    const swiper = new Swiper(".mySwiper", {
        modules: [Pagination],
        centeredSlides: true, //центрирование
        autoplay: {
            delay: 2500, //задержка при переключении слайдов
            defineEmitsisableOnInteraction: false, //переключение не останавливается никогда
        },
        pagination: {
            el: ".swiper-pagination",
            clickable: true,
        }
    })        
})
</script>

<template>
   <section class="opportunities" id="opportunities">
        <div class="container">
            <div class="opportunities-bg">
                  <h3>
                    Возможности
                  </h3>
                  <div class="row">
                      <div class="col-3">
                          <div class="opportunities__card-one">
                              <div class="opportunities__card-one-img-wrap">
                                  <img src="/sms.png" alt="">
                              </div>
                              <div class="opportunities__card-one-name">
                                  Общение с классом
                              </div>
                              <div class="opportunities__card-one-ps">
                                  Видеосвязь<br>Чат с классом
                              </div>
                          </div>  
                      </div>
                      <div class="col-3">
                          <div class="opportunities__card-two">
                              <div class="opportunities__card-two-img-wrap">
                                  <img src="/tv.png" alt="">
                              </div>
                              <div class="opportunities__card-two-name">
                                  Проведение занятий
                              </div>
                              <div class="opportunities__card-two-ps">
                                  Презентация файлов<br>Демонстрация экрана
                              </div>
                          </div>
                      </div>
                      <div class="col-3">
                          <div class="opportunities__card-one">
                              <div class="opportunities__card-one-img-wrap">
                                  <img src="/gg.png" alt="">
                              </div>
                              <div class="opportunities__card-one-name">
                                  Посещаемость
                              </div>
                              <div class="opportunities__card-one-ps">
                                  Автоматическое<br>отслеживание<br>присутствующих
                              </div>
                          </div>
                      </div>
                      <div class="col-3">
                          <div class="opportunities__card-two">
                              <div class="opportunities__card-two-img-wrap">
                                  <img src="/watch.png" alt="">
                              </div>
                              <div class="opportunities__card-two-name">
                                  История занятий
                              </div>
                              <div class="opportunities__card-two-ps">
                                  Материалы урока
                              </div>
                          </div>
                      </div>
                  </div>

                  <div class="mySwiper swiper">
                      <div class="wrapper swiper-wrapper">
                          <div class="cards swiper-slide">
                              <div class="opportunities__card-one-slider">
                                  <div class="opportunities__card-one-img-wrap-slider">
                                      <img src="/sms.png" alt="">
                                  </div>
                                  <div class="opportunities__card-one-name-slider">
                                      Общение с классом
                                  </div>
                                  <div class="opportunities__card-one-ps-slider">
                                      Видеосвязь<br>Чат с классом
                                  </div>
                              </div>
                          </div>
                          <div class="cards swiper-slide">
                              <div class="opportunities__card-two-slider">
                                  <div class="opportunities__card-two-img-wrap-slider">
                                      <img src="/tv.png" alt="">
                                  </div>
                                  <div class="opportunities__card-two-name-slider">
                                      Проведение занятий
                                  </div>
                                  <div class="opportunities__card-two-ps-slider">
                                      Презентация файлов<br>Демонстрация экрана
                                  </div>
                              </div>
                          </div>
                          <div class="cards swiper-slide">
                              <div class="opportunities__card-one-slider">
                                  <div class="opportunities__card-one-img-wrap-slider">
                                      <img src="/gg.png" alt="">
                                  </div>
                                  <div class="opportunities__card-one-name-slider">
                                      Посещаемость
                                  </div>
                                  <div class="opportunities__card-one-ps-slider">
                                      Автоматическое<br>отслеживание<br>присутствующих
                                  </div>
                              </div>
                          </div>
                          <div class="cards swiper-slide">
                              <div class="opportunities__card-two-slider">
                                  <div class="opportunities__card-two-img-wrap-slider">
                                      <img src="/watch.png" alt="">
                                  </div>
                                  <div class="opportunities__card-two-name-slider">
                                      История занятий
                                  </div>
                                  <div class="opportunities__card-two-ps-slider">
                                      Материалы урока
                                  </div>
                              </div>
                          </div>
                      </div>
                      
                      <div class="swiper-pagination"></div>
                  </div>
                  

              </div>
          </div>
      </section>
</template>

<style scoped>

</style>