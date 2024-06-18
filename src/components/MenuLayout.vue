<template>
  <v-layout>
    <v-app-bar density="compact" :elevation="0" color="#f2eeea">
      <v-app-bar-nav-icon variant="text" @click.stop="drawer = !drawer">
        <v-icon icon="mdi-apps"></v-icon>
      </v-app-bar-nav-icon>

      <!-- <v-toolbar-title>My files</v-toolbar-title> -->
      <v-spacer></v-spacer>
      Marcos Cruz Pascacio
      <v-spacer></v-spacer>
      <!-- <v-avatar>
             
            </v-avatar> -->
    </v-app-bar>

    <v-navigation-drawer v-model="drawer" :rail="false" permanent>
      <v-divider></v-divider>

      <v-list density="compact" nav>
        <v-menu location="end" transition="slide-x-transition">
          <template v-slot:activator="{ props: menu }">
            <v-tooltip location="end">
              <template v-slot:activator="{ props: tooltip }">
                <v-list-item
                  v-bind="mergeProps(menu, tooltip)"
                  prepend-icon="mdi-account"
                  title="My Account"
                  value="account"
                ></v-list-item>
              </template>
              <span>I'm A Tooltip</span>
            </v-tooltip>
          </template>
          <v-list style="margin-left: 10px">
            <RouterLink :to="{ name: 'users' }">
              <v-list-item v-for="(item, index) in items" :key="index">
                <v-list-item-title>{{ item.title }}</v-list-item-title>
              </v-list-item>
            </RouterLink>
          </v-list>
        </v-menu>
      </v-list>

      <template v-slot:append>
        <v-list>
          <v-list-item prepend-icon="mdi-logout" title="My Account"></v-list-item>
          <v-list-item prepend-icon="mdi-cog" title="My Account"></v-list-item>
        </v-list>
      </template>
    </v-navigation-drawer>

    <v-main>
      <router-view />
    </v-main>
  </v-layout>
</template>

<script lang="ts" setup>
import { ref } from 'vue'
import { mergeProps } from 'vue'
import { RouterLink } from 'vue-router'

var drawer = ref(false)
var items = ref([
  { title: 'Click Me1' },
  { title: 'Click Me2' },
  { title: 'Click Me3' },
  { title: 'Click Me4' }
])
</script>
