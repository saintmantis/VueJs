<template>
    <div >
        <center>
        <br><br><h2>E-mail</h2><br><br>
        <v-text-field class="vInput"
                v-model="Mail"
                label="Mail"
                placeholder="">
            </v-text-field>
        
        <v-text-field class="vInput"
                v-model="Password"
                label="Password"
                placeholder="">
            </v-text-field>
            <br><br>
        </center>
    </div>
</template>

<script>
</script>

<style scoped>
.vInput{
    width: 50%;
}
</style>