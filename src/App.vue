<script>
import AppBanner from './components/AppBanner.vue';
import AppStrengths from './components/AppStrengths.vue';
import AppAbout from './components/AppAbout.vue';
import AppServices from './components/AppServices.vue';
import AppPrices from './components/AppPrices.vue';
import AppBlog from './components/AppBlog.vue';
import AppNewsletter from './components/AppNewsletter.vue';
import AppContacts from './components/AppContacts.vue';
import AppFooter from './components/AppFooter.vue'

export default {
  components: {
    AppBanner,
    AppStrengths,
    AppAbout,
    AppServices,
    AppPrices,
    AppBlog,
    AppNewsletter,
    AppContacts,
    AppFooter
  }
}
</script>

<template>
  <AppBanner />
  <AppStrengths />
  <AppAbout />
  <AppServices />
  <AppPrices />
  <AppBlog />
  <AppNewsletter />
  <AppContacts />
  <AppFooter />
</template>

<style lang="scss">
@use "./styles/general.scss" as *;
</style>