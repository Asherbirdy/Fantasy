<script setup>



const aa = ref('aasdasdsadsd');
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

  <div class="wrapper">
      <HelloWorld msg="You did it!" />
{{ aa }}
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>
