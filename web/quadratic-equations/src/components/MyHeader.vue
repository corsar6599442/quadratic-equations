<template>
    <div class="MyHeader">
        <h1> {{ header }}</h1>
    </div>
</template>
<script>
export default {
  name: 'MyHeader',
  props: {
    header: String
  }
}
</script>