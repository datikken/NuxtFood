<template>
  <section class="container">
   <div class="categories">
     <div class="categories_menu">
      <a>Популярное</a>
      <a>Горячее</a>
      <a>Гарниры</a>
      <a>Выпечка</a>
      <a>Гриль</a>
      <a>Детское</a>
      <a>Закуски</a>
      <a>Супы</a>
      <a>Детское</a>
      <a>Закуски</a>
      <a>Супы</a>
      <a>Детское</a>
      <a>Закуски</a>
      <a>Супы</a>
      <a>Супы</a>
      <a>Детское</a>
      <a>Закуски</a>
      <a>Супы</a>
      <a>Супы</a>
      <a>Детское</a>
      <a>Закуски</a>
      <a>Супы</a>
     </div>
      <Categories/>
   </div>
   <div class="cart">
      Cart
   </div>
  </section>
</template>

<script>
import Categories from '~/components/Categories.vue'

export default {
  components: {
    Categories
  }
}
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-around;
}

.cart {
  background: yellow;
  width: 20rem;
}

.cart_heading {
  padding: 0;
}


.categories {
  width: 75%;
  background: purple;
}
.categories_menu {
  display: flex;
  overflow-x: auto;
  border-bottom: 1px solid black;

}

.categories_menu a {
  padding-top: 20px;
  margin-right: 30px;
}

.categories_menu::-webkit-scrollbar {
  display: none;
}


</style>
