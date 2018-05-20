<template>
  <div class="main">
    <div class="container">
      <h2>What We Are All About</h2>
      <div class="text">
        <p>
          It’s not always easy to filter out noise and purely focus on the content. Too many blogs and news sites are
          filled with colourful and distracting
          advertisement left right and centre. This is where we do things differently! Rather than just focusing purely
          and generating revenue, we focus
          on great user experience.
        </p>
        <p>
          You will notice that our news articles are content focused and free of any distractions. On top of that, we
          deliver content revolving design on a
          daily basis. Offering you insightful tutorials, techniques, design inspirations, mobile app development,
          coding, unique advertisements, and
          freebies.
        </p>
        <p>
          Our focus is and forever will be to bring high quality resources to lean from and to be inspired. Visit us
          daily for new design related articles!
        </p>
      </div>
      <hr>
      <h2>Meet Our Team!</h2>
      <div class="team">
        <div class="team__item">
          <team-item/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  import TeamItem from '@/components/TeamItem'
  export default {
    name: 'AboutPage',
    components: {
      TeamItem
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  h1, h2 {
    font-weight: normal;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }
</style>
