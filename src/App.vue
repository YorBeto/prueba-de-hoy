<script setup>
</script>

<template>
    <v-container class="fill-height" >
      <v-row>
        <v-col cols="6" offset="3">
          <v-card>
          <v-card-title class="bg-cyan">Iniciar sesion</v-card-title>
          <v-card-text>
            <v-container>
              <v-row>
                <v-col cols="3">Usuario:</v-col>
                <v-col><v-text-field label="user" variant="outlined"></v-text-field></v-col>
              </v-row>
              <v-row>
                <v-col cols="3">Contraseña:</v-col>
                <v-col><v-text-field label="password" variant="outlined"></v-text-field></v-col>
              </v-row>
            </v-container>
          </v-card-text>
          <v-card-actions>
            <v-container>
              <v-row justify="end">
                <v-col class="d-flex justify-end">
                <v-btn @click="alerta" size="x-large" variant="flat" color="red">Login</v-btn>
              </v-col>
              </v-row>
            </v-container>
          </v-card-actions>
        </v-card>
        </v-col>
      </v-row>
    </v-container>
</template>

<style scoped>

</style>