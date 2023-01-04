<template>
  <div>
    <Html lang="en" />
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<script>
export default {
  methods: {
    splitbee() {
      const { SplitbeeAnalytics } = require("@splitbee/node");
      const analytics = new SplitbeeAnalytics("HC52KM9FUODR");
      analytics.track({
        userId: "DN1B7754F3XE",
      });
    },
  },
};
</script>

<style>
@media only screen and (min-width: 600px) {
  .page-leave-active {
    transition: all 0.5s;
  }
  .page-enter-active {
    transition: all 0.5s;
  }
  .page-enter-from {
    transform: scale(1.2);
  }
  .page-leave-to {
    transform: scale(0);
    opacity: 0;
  }
}
/* @media only screen and (max-width: 600px) {
  .page-leave-active {
    transition: all 0.5s;
  }
  .page-enter-active {
    transition: all 0.5s;
  }
  .page-enter-from {
    transform: scale(0.5) translateX(-150%);
  }
  .page-leave-to {
    transform: scale(0.5) translateX(150%);
    opacity: 0;
  }
} */
</style>
