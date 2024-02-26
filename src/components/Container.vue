<template>
  <div>
    <PostBox />
    <PostBox />
    <PostBox />
  </div>
</template>

<script>

import PostBox from './Post.vue';

export default {
    name: 'ContainerBox',
    components: {
        PostBox: PostBox,
    },
}
</script>

<style>

</style>