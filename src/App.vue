<template>
  <div>
    <ul>
      <li>
        <router-link :to="{path: '/table'}">table</router-link>
      </li>
      <li>
        <router-link :to="{path: '/table', query: {name: 'xxx1'}}">table?name=xxx1</router-link>
      </li>
      <li>
        <router-link :to="{path: '/table', query: {name: 'xxx5'}}">table?name=xxx5</router-link>
      </li>
    </ul>
    <div class="col-sm-10">
    <router-view></router-view>
  </div>
  </div>
</template>

<script>

export default {
  name: 'App'
}
</script>
