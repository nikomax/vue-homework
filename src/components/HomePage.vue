<template>
  <div class="articles">
    <div class="container">
      <main-article
        article-title="Our Favourite Task Management App!"
        article-date="Posted on March 28, 2013"
        article-image="../assets/image.jpg">
        <p>6Wunderkinder’s flagship product, Wunderlist, has been a massive hit since its inception. Arguably one of the best to manage your
          tasks in your business and personal life. What makes it different from any other app? Simplicity. You don’t need to fiddle around with
          so many unnecessary features like you would with traditional to-do apps. Soon as you open the app, Wunderlist dives right into your
          tasks and you can get to work.
        </p>
      </main-article>
      <main-article
        article-title="Year in Review: Our Favourite Apps from 2012 "
        article-date="Posted on March 3, 2013"
        article-image="../assets/image.jpg">
        <p>The iPad mini is the newly introduced member of the “i” family. Pixeden has done a phenomenal job of replicating iPad Mini into a
          vector form and has made it freely available for everyone to use. A second version of the iPhone 5 mockup template released by
          Pixeden, which is the couterpart to the originally released black version. This template also includes high quality background floor
          textures.
        </p>
      </main-article>
    </div>
  </div>
</template>

<script>
import MainArticle from '@/components/MainArticle'
export default {
  name: 'HomePage',
  components: {
    MainArticle
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="sass">

</style>
