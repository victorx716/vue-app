<template>
  <div class="box">
    <div class="apps">
     App One 
    </div>  
    <div class="apps">
     App Two 
    </div>  
    <div class="apps">
     App Three 
    </div>          
  </div>
</template>

<script>
export default {
  name: 'Container'
}
</script>

<style scoped>
.box {
  display: inline-block;
  border-bottom: 2px solid lavender;
  padding: 10px;
}

.apps {
  margin: 20px 0px 20px 0px;

}

</style>