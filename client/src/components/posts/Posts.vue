<template>
  <div class="container mt-3">
    <div>
      <b-nav>
        <b-nav-item active>
          <router-link class="mr-3" :to="{name: 'AllPosts'}" active>All Posts</router-link>
        </b-nav-item>
        <b-nav-item active>
          <router-link class="mr-3" :to="{name: 'CreatePost'}" active>Create Post</router-link>
        </b-nav-item>
      </b-nav>
    </div>
    <router-view/>
  </div>
</template>
<style lang="scss" scoped>
a {
  text-decoration: none;
  font-size: 1.5rem;
  color: #888 !important;
}
.router-link-exact-active {
  text-decoration: underline;
}
</style>

