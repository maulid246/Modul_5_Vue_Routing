<template>
    <div>
        <h1> {{msg}} </h1>
    </div>
</template>

<style scoped>
h1 {
    color:aqua;
    padding: 10px 50px;
    background-color:azure;

}
</style>
<script>
export default {
   name: "nama",
   props: {
       msg : String
   }
   
}
</script>