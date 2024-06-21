<script setup>
const projects = [
    {
        src:"/one.png",
        title:'Составьте расписание',
        text:"Выберите время, предмет и класс. Ученики получат уведомление о предстоящем уроке.", 
    },
    {
        src:"/docs.png",
        title:'Подготовьте материал',
        text:"Загружайте необходимые материалы<br>к уроку.", 
    },
    {
        src:"/girls.png",
        title:'Начните урок с учениками',
        text:"Задавайте вопросы и вызывайте<br>«к доске» детей с поднятой рукой.", 
    }
]
</script>

<template>
   <section class="materials" id="materials">
          <div class="container">
              <h3>
                  Как это работает?
              </h3>
              <div class="row">
                  <div class="col-lg-4 col-sm-12" v-for="(item, index) in projects" :key="projects">
                      <div class="materials__card">
                          <div class="materials__card-img-wrap">
                              <img :src="item.src" alt="">
                          </div>
                          <div class="materials__card-name">
                              {{item.title}}
                          </div>
                          <div class="materials__card-ps">
                              {{item.text}}
                          </div>
                      </div>
                  </div>
              </div>
          </div>
      </section>
</template>

<style scoped>

</style>