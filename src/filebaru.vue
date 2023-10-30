<template>
    <h1>Hallo disini saya mencoba membuat file vue</h1>
    <p>{{ email }}</p>
    <p>{{ getData().email }}</p>
    <p>Name: {{  getName("Atheo") }}</p>
</template>

<script>
export default {
    name: "filebaru",
    data(){
        return{
            email: "belajar@gmail.com"
        }
    },
    methods:{
        getName(name){
            return name;
        },
        getData(){
            return {
            email: "belajarMethods@gmail.com",
            phone: "0821444555"
            }
            
        }
    }
}
</script>