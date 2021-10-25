<template>
  <div class="entry-container nb-3 pointer p-2"
       @click="$router.push({ name: 'entry', params: {id: 10} })">
    <div class="entry-title d-flex">
      <span class="text-success fs-5 fw-bold">15</span>
      <span class="mx-1 fs-5"> Julio</span>
      <span class="mx-2 fx-light">2021, jueves</span>
    </div>

    <div class="entry-description">
      Veniam sit ipsum aliqua reprehenderit mollit reprehenderit magna. Proident
      ullamco ea adipisicing minim magna ex eiusmod eu esse elit nulla.
      Adipisicing consequat ea cillum excepteur. Occaecat mollit sunt Lorem
      incididunt ut commodo ad enim consequat consequat dolor aliquip nisi. Aute
      irure voluptate consequat amet duis minim nulla est velit consectetur
      tempor ipsum. Aute esse ad nisi commodo et nulla dolore eu non duis anim
      ea quis. Occaecat do ut ad ex exercitation sint est aute ad exercitation
      sunt eiusmod.
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.entry-container  {
  border-bottom: 1px solid #2c3e50;
  transition: 0.2s all ease-in;

  &:hover {
    background-color: lighten($color: gray, $amount: 45);
    transition: 0.2s all ease-in;
  }
  .entry-description {
      font-size: 12px;
  }
}
</style>