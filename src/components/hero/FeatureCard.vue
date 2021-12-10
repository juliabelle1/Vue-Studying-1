<template>
   <div class="col-md-6 mb-5">

          <i class="fas fa-gem fa-3x blue-text"></i>

          <p class="font-weight-bold my-3">First action</p>

          <p class="text-muted mx-md-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit tempora facere
            quos, repudiandae sunt maiores.</p>

          <a v-on:mouseover="handleMouseOver" @click="clickFunction" class="btn btn-success btn-md" href="#" role="button">{{btnText}}</a>

        </div>
</template>

<script>
export default {
  data(){
    return{
      btnText: 'click me'
    }

  },
  methods:{
    handleMouseOver(){
      console.log('mouse over')
    },
    clickFunction(){
      console.log('click on button')
    }
  }
}
</script>

<style>

</style>