<template>
  <div class="page">
    <div class="nav">
      <ul>
        <li>
          <nuxt-link to="/settings">General</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/settings/deck">Deck</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/settings/schedule">Schedule</nuxt-link>
        </li>
      </ul>
    </div>
    <main class="main">
      <nuxt-child />
    </main>
  </div>
</template>

<script>
export default {
  name: 'PageSettingParent',
}
</script>
<style lang="scss">
.page {
  display: flex;

  .main {
    margin-left: 7px;
  }
}
</style>
