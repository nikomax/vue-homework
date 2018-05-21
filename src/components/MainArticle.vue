<template>
  <article class="article">
    <h2 class="article__title common-title">
        {{ articleTitle }}
    </h2>
    <div class="article__date">
      {{ articleDate }}
    </div>
    <div class="article__image">
      <img :src="articleImage" alt="">
    </div>
    <div class="article__text">
      <slot></slot>
    </div>
    <a href="#" class="more-link"><img src="../assets/more-icon.png" alt="">Read More</a>
  </article>
</template>

<script>
  export default{
    props: ['articleTitle', 'articleDate', 'articleImage'],
  };
</script>

<style lang="sass">
.article
  padding-bottom: 50px
  &__title
    margin-bottom: 15px
  &__date
    text-align: center
    font-size: 14px
    color: #777777
    margin-bottom: 45px
  &__image
    width: 330px
    height: 290px
    border: 1px solid #b0b0b0
    margin: 0 auto 50px
    img
      height: 100%
      width: 100%
      object-fit: cover
  &__text
    margin-bottom: 22px

</style>
