<template>
  <el-input placeholder="Please input" v-model="input">
  </el-input>
</template>

<script lang="ts">
  import {
    Component,
    Vue,
  } from 'vue-property-decorator';
  import {
    Input,
  } from 'element-ui';

  Vue.use(Input);
  @Component
  export default class UseElement extends Vue {
    private input: string = '';
  }
</script>