<template>

<section class="header">
  <h1>Checking sending and recieving git commit sync</h1>
  <span>Learning GIT  + VueJS</span>
  <p>Testing the a = {{ a }}</p>
  <p>obj = {{obj}}</p>
</section>

</template>

<script>
const test = 'var'

export default {
  data() {
    return {
      a: 123,
      b:'переменная б',
      obj: {
        a: 1,
        b: 2,
        c: test
      }
    }
  }
}
</script>

<style>

.header {
  background: tomato;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;

}

h1 {
  color: #fff;
}

span {
  color: #fff;
  font-size: 22px;

}

</style>
