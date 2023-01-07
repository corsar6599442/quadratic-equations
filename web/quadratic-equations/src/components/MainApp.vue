<template>
    <div class="MainApp">
        <h1> {{ message }}</h1>
        <input>
    </div>
</template>
<script>
export default {
  name: 'MainApp',
  props: {
    message: String
  },
  // data: {
  //   a: '',
  //   b: '',
  //   c: '',
  //   liter: 'a',
  //   inputMessage: `Введите ${liter}`
  // },
  // methods: {
  //   removeInput: function () {
  //     return inputMessage = ''
  //   }
  // }
}
</script>