<template>
<div id="pro">
  <v-card
    class="mx-auto"
    max-width="400"
  >
    <v-img
      class="white--text align-end"
      height="200px"
      src="https://yt3.googleusercontent.com/c8p88q6z6Ba5q3053k7rcNV_7fgardb5Z0vMnisGoyS7ht1PN_sF5xhu4G1j_ZrBdK8W_Usj=s900-c-k-c0x00ffffff-no-rj"
    >
    </v-img>

    <v-card-subtitle class="red">
      <h1>Pongtong Pongsombat</h1>
    </v-card-subtitle>
    
    <v-card-text class="text--primary">
      <div></div>

      <div>พงษ์ทอง พงษ์สมบัติ (พีท)</div>
      
    </v-card-text>

    <v-card-text class="text--primary">
      <div></div>

      <div>อายุ 21 ปี </div>
      <div>เขียนโปรแกรมไปวันๆ </div>
    </v-card-text>

    <v-card-actions>
      <v-btn
        color="orange"
        text
      >
        ติดต่อ
      </v-btn>

      <v-btn
        color="orange"
        text
      >
        จ้าง
      </v-btn>
    </v-card-actions>
  </v-card>
  </div>
</template>
<style>
#pro {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh; /* กำหนดความสูงของ div เท่ากับความสูงของ viewport */
}
</style>

<script>
export default {
   name: 'HelloWorld',

   data: () => ({
      
   })
}
</script>
