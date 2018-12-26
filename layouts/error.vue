<template>
  <div class="uk-section-muted">
    <navbar class="uk-navbar-transparent"></navbar>

    <div
      class="uk-section uk-section-small uk-flex uk-flex-middle uk-text-center"
      uk-height-viewport="offset-top: true; offset-bottom: true"
    >
      <div class="uk-width-1-1">
        <div class="uk-container">
          <div>
            <div class="uk-text-lead">
              <div
                class="uk-heading-primary uk-animation-slide-left-small"
                style="animation-delay: 0.4s"
              >404</div>
              <div
                class="uk-animation-slide-left-small"
                style="animation-delay: 0.7s"
              >Page Not Found...</div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="uk-section-small">
      <div
        class="uk-container uk-container-expand uk-text-center uk-position-relative uk-animation-slide-left-small"
        style="animation-delay: 1s"
      >
        <footer class="uk-text-meta">
          Powered by
          <a href="https://imst.xyz/">Demo Macro</a>
        </footer>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ["error"],
//   layout: "blog" // 你可以为错误页面指定自定义的布局
};
</script>