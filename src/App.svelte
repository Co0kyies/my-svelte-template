<script></script>

<section class="hero is-medium is-info">
  <div class="hero-body">
    <div class="container">
      <div class="columns">
        <div class="column">
          <p class="title">Hello World!</p>
          <p class="subtitle">This is my svelte setup</p>
        </div>
        <div class="column">
          <div class="box">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta
            aliquid labore id totam delectus quod adipisci quidem fuga ad iusto,
            molestiae ipsum aliquam tempora nostrum repudiandae, aspernatur
            architecto. Alias, aut.
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
<section class="section with-sass">
  <div class="box">
    <p class="subtitle">With Sass</p>
  </div>
</section>

<style lang="scss">
  @import "breakpoint_mixins.scss";
  .with-sass > .box {
    @include mobile {
      background-color: aqua;
      .subtitle {
        color: White;
      }
    }
    @include tablet {
      background-color: aquamarine;
    }
    @include desktop {
      background-color: crimson;
    }
    @include wildscreen {
      background-color: darkorange;
    }
  }
</style>
