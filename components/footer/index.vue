<template>
  <div>
    <v-row>
      <v-col lg="3">
        <v-list>
          <v-list-item v-for="n in 5" :key="n"> sdfa </v-list-item>
        </v-list>
      </v-col>
      <v-col lg="3">
        <v-list>
          <v-list-item v-for="n in 5" :key="n"> sdfa </v-list-item>
        </v-list>
      </v-col>
      <v-col lg="2">
        <v-list>
          <v-list-item v-for="n in 5" :key="n"> sdfa </v-list-item>
        </v-list>
      </v-col>
      <v-col lg="4" class="">
        <v-list height="100%">
          <v-list-item v-for="n in 3" :key="n"> sdfa </v-list-item>
        </v-list>
      </v-col>
    </v-row>
  </div>
</template>
