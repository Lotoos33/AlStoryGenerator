<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      Make your dream's come true! <p>We using:
      <a href="#" target="_blank" rel="noopener">GPT-3</a></p> 
    </h3>

    <button><a href="#">Start Here!</a></button>
  </div>
</template>

<style scoped> 
 button {
  display: flex;
  margin: 0 auto;
  background-color: transparent;
  border: none;
  font-size: 20px;
  padding-top: 0.6rem;
 }

h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 0.9rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
