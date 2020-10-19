<template>
<v-card>
  <!-- <v-app> -->
    
    <v-toolbar>
      

      <v-app-bar>
      <v-app-bar-nav-icon @click.native="sideNav = !sideNav"></v-app-bar-nav-icon>
      <v-toolbar-title> RidMeetUp</v-toolbar-title>
      <v-navigation-drawer v-model="sideNav">

      </v-navigation-drawer>

    <v-spacer></v-spacer>
      <v-toolbar-items>
        <v-btn text> 
          <!-- <v-icon left>supervisor_account</v-icon> -->
          View Meetups
        </v-btn>
      </v-toolbar-items>
      </v-app-bar>
      
      <!-- <v-toolbar-side-icon @click.native="sideNav = !sideNav"></v-toolbar-side-icon> -->
      
      
    </v-toolbar>

    <v-main>
  
    </v-main>
  <!-- </v-app> -->
</v-card>
</template>

<script>


export default {
  data: function () {
                return {
                  sideNav: false
                }
               
            },

  
};
</script>

<style lang="scss" scoped>
.v-toolbar__content, .v-toolbar__extension {
    padding: 0px; 
}

</style>
