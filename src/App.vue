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
   <div class="row row-cols-1 row-cols-md-3 g-4">
  <div class="col">
    <div class="card h-100">
      <div class="card-body">
        <h5 class="card-title">HP</h5>
        <p class="card-text">500.000 ₸</p>
        <p class="card-text">X10</p>
        <p class="card-text">25.11.2024</p>
      </div>
      <div class="card-footer text-end">
        <button class="btn btn-outline-danger">Удалить</button>
      </div>
    </div>
  </div>
</div>
<div class="row my-4">
 <div class="col">
<h3 class="text-end">Общая сумма товаров: ₸2.535.800 </h3>
 </div>
</div>
</div>


</template>

