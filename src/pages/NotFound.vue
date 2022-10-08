<template>
  <section>
    <base-card>
      <h2>Page Not Found ❌</h2>
      <h4>
        This page could not be found - please try again or visit our
        <router-link to="/coaches">
          <span class="link">
            Coaches
          </span> </router-link
        >.
      </h4>
    </base-card>
  </section>
</template>
<style scoped>
.link {
  color: blue;
}
.link:hover {
  color: red !important;
}
</style>
