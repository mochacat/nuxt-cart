<template>
  <div class="product-section">
    <img src="../assets/img/computer.png" alt="Computer" class="product" />
    <div class="product-detail">
      <h2 class="product-name">{{ name }}</h2>
      <p class="product-description">{{ description }}</p>
      <p class="product-price"> Price: {{ price }}</p>
    </div>
  </div>
</template>

<script>
  export default {
    data: () => ({
      name: 'All-in-one Desktop PC',
      description: 'Behold the integrated design of this personal computer.',
      price: '375.00'
    })
  }
</script>
