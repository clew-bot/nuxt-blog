<template>
    <section class="post-list">
      <PostPreview 
      id="1"
      thumbnail="https://cdn-media-1.freecodecamp.org/ghost/2019/03/vueart.png"
      title="Hello there!"
      previewText="Vue is all around solid"/>
      <PostPreview 
      id="2"
      thumbnail="https://easybase.io/assets/images/posts_images/5-great-react-libraries-1.png"
      title="Hello there!"
      previewText="React is better"/>
      <PostPreview 
      id="3"
      thumbnail="https://cdn.searchenginejournal.com/wp-content/uploads/2019/04/the-seo-guide-to-angular-760x400.png"
      title="Hello there!"
      previewText="Angular sucks"/>
    </section>
</template>

<script>
import PostPreview from '@/components/Posts/PostPreview'
export default {
    components: {
        PostPreview
    }
}
</script>

<style scoped>

.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>