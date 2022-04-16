<template>
<div class="first__frame">
  <h1>
    <a v-bind:href="url"><img src="../assets/googlelogo_color_272x92dp.png"></a>
    <p> {{ Number(sto) + Number(inp) }} </p>
  </h1>
  <input v-model="inp">
</div>
</template>



<script>
export default {
  name: 'FirstTraning',
  data () {
    return {
      url: 'https://www.google.com',
      sto: 100,
      inp: ''
    }
  }
}

</script>

<style lang="css" scoped>
.first__frame {
  display: grid;
  justify-content: center;
}
h1 {
  color: lightslategray;
  font-size: 46px;
}

a {
  text-decoration: none;
  color: lightslategray;
  margin-bottom: 30px;
}

input {
  padding: 0px 30px;
  border-radius: 24px;
  border: 1px solid #e3e3e3;
  background-color: #fff;
  transition: all 0.1s;
  width: 540px;
  height: 46px;
}

input:hover {
  box-shadow: 0 1px 6px rgb(32 33 36 / 28%);
}

input:focus-visible {
  outline: none;
  box-shadow: 0 1px 6px rgb(32 33 36 / 28%)
}

</style>