<i18n src="~/locales/components/PageFooter.yml"></i18n>
<i18n src="~/locales/global.yml"></i18n>

<style lang="scss" scoped>
footer {
  box-shadow: 0 0 40px rgba(0, 0, 0, 0.4);

  img {
    margin: $spacer;
    max-height: 100px;
    max-width: 200px;
  }
}
.arrow-up {
  @include arrow-up($body-bg);
}
</style>

<template>
  <footer class="text-center">
    <div class="bg-gray-light p-4">
      {{ $t('built_by') }}<br>
      <div class="d-flex align-items-center flex-wrap">
        <div class="col-md-4">
          <a href="https://www.colorofchange.org" target="_blank">
            <img src="/logos/Color of Change.png" alt="Color of Change">
          </a>
        </div>
        <div class="col-md-4">
          <a href="https://www.mediajustice.org" target="_blank">
            <img src="/logos/MediaJustice.png" alt="MediaJustice">
          </a>
        </div>
        <div class="col-md-4">
          <a href="https://www.freepress.net" target="_blank">
            <img src="/logos/free-press.jpeg" alt="Free Press">
          </a>
        </div>
      </div>
    </div>
  </footer>
</template>
