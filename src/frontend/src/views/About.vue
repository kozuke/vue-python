<template>
  <div class="about">
    <test msg="test"/>
    <test msg="test"/>
    <test msg="test"/>
    <test msg="test"/>
    <test2 msg="test2"/>
    <test2 msg="test2"/>
    <test2 msg="test2"/>
    <test2 msg="test2"/>
    <test3 msg="test3"/>
    <test3 msg="test3"/>
    <test3 msg="test3"/>
    <test3 msg="test3"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import test from '@/components/test.vue'; // @ is an alias to /src
import test2 from '@/components/test2.vue'; // @ is an alias to /src
import test3 from '@/components/test3.vue'; // @ is an alias to /src

@Component({
  components: {
    test,
    test2,
    test3,
  },
})
export default class About extends Vue {}
</script>
