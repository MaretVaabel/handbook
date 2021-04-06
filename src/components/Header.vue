<template>
<div>
    <header class="py-2 ">
        <div class="container h-100">
            <div class="row h-100">
                <div class="my-auto text-white text-center">
                    <h2>Veebipõhiste õppematerjalide juhendid</h2>
                </div>              
            </div>          
        </div>
    </header>
</div>
    
</template>

<script>

export default {
    name: 'Header',
  components: {
  
  }
    
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Permanent+Marker&family=Playfair+Display&family=Roboto&display=swap');
header {
    background-color: gray;
    height: 150px;
    width: 100%;
    margin-top: 50px; 
    font-family: 'Permanent Marker', cursive;
}
/* h2 {
    
    font-size:8vmin;
} */


@media screen and (min-width: 530px){
  header {
      height: 200px;
  }

  h2 {
      font-size: 60px;
  }
}
</style>