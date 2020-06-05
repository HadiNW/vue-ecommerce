<template>
  <div>
    <Header />
    <router-view/>
  </div>
</template>

<script>
import Header from './components/header/header.component'

export default {
  components: {
    Header
  }
}
</script>

<style lang="scss">

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  font-size: 16px;
}

body {
  font-family: 'Poppins', sans-serif;
}

a {
  color: #000;
  text-decoration: none;
}

.btn-primary {
  background: #E61E1C;
  cursor: pointer;
  color: #fff;
  border: 1px solid #fff;
  padding: .5rem .7rem;
  border-radius: .3rem;

  &:hover {
    background: #cf4f4d;
  }
  &:focus {
    outline: none;
  }
}
</style>
