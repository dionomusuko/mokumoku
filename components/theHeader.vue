<template>
  <v-card color="grey lighten-4">
    <v-toolbar extended>
      <v-toolbar-title>ワイのポートフォリオ</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-home</v-icon>
      </v-btn>

      <v-btn icon href="github_url">
        <v-icon>mdi-github</v-icon>
      </v-btn>

      <v-btn icon href="twitter_url">
        <v-icon>mdi-twitter</v-icon>
      </v-btn>
    </v-toolbar>
  </v-card>
</template>

<script>
export default {
  name: 'theHeader',
  //自分のアカウントに変える
  github_url: 'https://twitter.com',
  twitter_url: 'https://github.com'
}
</script>

<style></style>
