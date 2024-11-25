<script setup>

</script>

<template>
<div class="container">
   <div class="row">
    <h1 class="text-center my-3">  Учет товара</h1>
       <div class="rol">
          <div class="mb-3">
              <label for="name" class="form-label">Продукт</label>
              <input type="text" class="form-control" id="name">
          </div>
          <div class="mb-3">
              <label for="date" class="form-label">Дата</label>
              <input type="date" class="form-control" id="Date">
          </div>
          <div class="mb-3">
              <label for="count" class="form-label">Количество</label>
              <input type="number" class="form-control" id="count">
          </div>
          <div class="mb-3">
              <label for="price" class="form-label">Цена</label>
              <input type="number" class="form-control" id="count">
          </div>
          <button type="button" class="btn btn-outline-primary">Добавить</button>
       </div>
   </div>
</div>

</template>

