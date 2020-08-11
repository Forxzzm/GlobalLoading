<template>
  <div>
    
  </div>
</template>

<script>
export default {
  components: {},
  props: {},
  data() {
    return {
    }
  },
  created() {},
  mounted() {
    //简单默认多个组件调用。
    let test1 = this.$loading({loadText:'111'});
    let test2 = this.$loading({loadText:'111'});
    let test3 = this.$loading({loadText:'111'});
    this.$loading();
    //模拟异步请求
    setTimeout(() => {
      test1.close();
      test2.close();
      test3.close();
    }, 3000);
  },
  computed: {},
  watch: {
  },
  methods:{}
}
</script>

<style >
</style>