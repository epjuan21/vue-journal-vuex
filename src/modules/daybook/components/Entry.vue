<template>
  <div @click="$router.push({ name: 'entry', params : { id: 10 }})" class="entry-container mb-3 pointer p-2">
    <!-- Titulo -->
    <div class="entry-title d-flex">
      <span class="text-success fs-5 fw-bold">15</span>
      <span class="mx-1 fs-5">Julio</span>
      <span class="ms-2 fw-light">2021, jueves</span>
    </div>

    <div class="entry-description">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit
      temporibus officiis molestiae ea ex cumque pariatur, nihil ipsam
      doloremque consectetur earum blanditiis ad iure iste adipisci
      exercitationem minus aliquid voluptatibus.
    </div>
  </div>
</template>

<style lang="scss" scoped>
.entry-container {
  border-bottom: 1px solid #2c3e50;
  transition: 0.2s all ease-in;

  &:hover {
    background-color: lighten($color: grey, $amount: 45);
    transition: 0.2s all ease-in;
  }
  .entry-description {
    font-size: 12px;
  }
}
</style>
