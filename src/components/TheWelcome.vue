<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Documentation</template>

    StoryAI is a web application that uses artificial intelligence to generate unique and engaging stories. That's why we have open documentation for you <a href="#">Here</a>!
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tooling</template>

    <p><h4>Generate stories based on user-defined parameters:</h4> Simply provide keywords, select a genre and desired length, and StoryAI  will do the rest.</p>
    <p><h4>Customize genres and styles:</h4> Choose from a wide range of genres, including fantasy, science fiction, romance, mystery, thriller, and many more. You can also customize the tone and style of your story to match your preferences.</p>

    <br />

    More informations are available in <a href="#">Here</a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Benefits:</template>
    <ul><li><h4>Explore new storytelling techniques</h4></li>
    <li><h4>Improve your writing</h4></li>
    <li><h4>Generate creative content</h4></li>
    <li><h4>Have fun and explore</h4></li></ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>

    Any interesting idea? See any error? Join our Discord <a href="#">Here</a>! <p>Let us know about it!</p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support AIStoryGenerator</template>

    As an independent project, AI Story Generator relies on community backing for its sustainability. You can help
    us by
    <a href="#" target="_blank" rel="noopener">becoming a sponsor</a>.
  </WelcomeItem>

  
</template>

<style scoped>
h4 {
  color: hsla(160, 100%, 37%, 1);
}

h4:hover {
  color: rgb(1, 160, 107);
  font-weight: 900;
  font-size: medium;
  cursor: default;
}
</style>
