<template>
  <div class="list">
    <div class="list__wrapper">
      <div class="list__pic"></div>
      <div class="list__title">
        <p class="list__titleItem">{{ title }}</p>
      </div>
      <div class="list__text">
        <p class="list__textItem">{{ text }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true,
    },
    text: {
      type: String,
      required: true,
    },
  },
  data() {
    return {}
  },
}
</script>
<style scoped>
.list__wrapper {
  padding: 33px;
}
.list__title {
  width: 60%;
  height: 40px;
  background: #b6fffb;
  border-radius: 10px;
  margin-bottom: 30px;
}
.list__titleItem {
  padding-top: 10px;
  padding-left: 15px;
}
</style>
