<template>
  <div class="test">
    <p>{{data}}</p>
  <a-input placeholder="Basic usage" />
  <button v-on:click="test">Click me</button>  
  </div>
</template>

<script>
import Vue from "vue";
import {Input} from "ant-design-vue";
Vue.use(Input);
export default {
  name: "DevTest",
  props: {
    data: String
  },
  methods: {
    test: function(event){
      console.log("My name is " + this.data);
      if(event) console.info(event.target.tagName);
    } 
  }
}
</script>
