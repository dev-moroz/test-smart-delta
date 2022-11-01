<template>
   <div class="card">
      <div class="title">
         <img alt="subtract" src="../assets/Subtract.svg">
         <p>{{ title }}</p>
      </div>
      <button>{{ button }}</button>
   </div>
</template>

<script>
import {ref} from 'vue'
export default{
   setup(){
      const title = ref('Title Big mob')
      const button = ref('Label mob')
      return {
         title,
         button
      }
   }
}

</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500;700&display=swap');

.card{
   background: linear-gradient(90deg, #E81F2F 0%, #FF8983 100%);
   border-radius: 20px;
   display: flex;
   justify-content: space-between;
   align-items: center;
   padding: 0 8px 0 16px;
   max-height: 52px;
   max-width: 375px;
   min-width: 260px;
   width: 100%;
}
.title{
   display: flex;
   gap: 10px;
}
p{
   color: #fff;
   font-weight: 700;
   font-family: 'Montserrat', sans-serif;
}
button{
   color: #E81F2F;
   background-color: #fff;
   border-radius: 12px;
   padding: 8px 16px;
   border: none;
   font-weight: 500;
   font-size: 14px;
   line-height: 20px;
}
button:hover{
   cursor: pointer;
}
</style>