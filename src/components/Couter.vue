<template>
  <div>
    <button @click="$store.commit('increment')">+</button>
    <span>{{$store.state.count}}</span>
    <button @click="$store.commit('decrement')">-</button>
  </div>
</template>

<script>
export default {
    data(){
        return {

        }
    },
    methods:{
        
    }
};
</script>