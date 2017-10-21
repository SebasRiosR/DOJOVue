<template>
  <div>
  <h2>Home</h2>
  <input v-model="message" placeholder="edit me" name="entrada">
  <button v-on:click="Click">Tomar palabra</button>
  <p>Message is: {{ message2 }}</p>
  </div>
</template>

<script>
export default {
data (){
    return {
    	message: "",
    	message2: ""
    }
  },
  methods:{
	Click() {
		this.message2 = this.message
	}
}
}
</script>

<style>
</style>

