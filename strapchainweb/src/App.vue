<template>
  <v-app>
  <div>
    <v-app-bar
      color="white"
      dense
      dark
    >
      <v-app-bar-nav-icon>
        <img src="./assets/img 1.png" width="30" height="30">
      </v-app-bar-nav-icon>

      <h2 class="text-tittle black--text">Strapchain</h2>

      <v-tabs>
      <v-spacer></v-spacer>
      
      <v-tab class="black--text">About</v-tab>

      <v-tab class="black--text">Contact</v-tab>

      <v-tab class="black--text">Feedback</v-tab>
      </v-tabs>
      <v-menu
        left
        bottom
      >
        <v-list>
          <v-list-item
            v-for="n in 5"
            :key="n"
            @click="() => {}"
          >
            <v-list-item-title>Option {{ n }}</v-list-item-title>
          </v-list-item>
        </v-list>
      </v-menu>
    </v-app-bar>
  </div>
 

  <!-- Sizes your content based upon application components -->
  <v-main>

    <!-- Provides the application the proper gutter -->
    
    <v-img src="./assets/img 2.png" width="1400" height="550">

    <v-row  
    align="center"
    justify="center"
    style="height: 550px;"
    no-gutters
    wrap>

    <v-card-text class="text-center align-center">
      <h1 class="red--text">Capture </h1>   
    <v-card-text>
      <h1 class="red--text">Your Beautiful Moments</h1>
    <v-card-text class="text-center">
      <h3>PHOTO CUSTOM KEYCHAIN</h3>
      </v-card-text>
    <v-btn
      color="white"
      elevation="6"
    >ORDER NOW>></v-btn>
    </v-card-text>
    </v-card-text>
    </v-row>
    </v-img>

    <center>
      <img src="./assets/img 3.png" width="30" height="30" class="mt-5">
      <v-card-text>
        Strapchain adalah sebuah website yang berdiri pada 2021 yang bermula dari para pelajar SMK Negeri 8 Malang yang mendapatkan tugas untuk membuat sebuah website yang mana nantinya website tersebut akan menjadi tempat promosi produk kami yaitu gantungan kunci custom, oleh karena itu tercetuslah untuk membuat Website ini sebagai alat promosi kami selain sosial media.
      </v-card-text>
    </center>

    <v-img src="./assets/img 4.png" width="1400" height="450">
    <center>
    <v-card-text class="red--text"><h2>Collection</h2></v-card-text>
    
    <v-row>
    <v-col
      cols="6"
      sm="4"
    >
      <v-img
        src="./assets/img 5.jpg" width="350" height="350" class="mt-5"> 
      </v-img>
    </v-col>

    <v-col
      cols="6"
      sm="4"
    >
      <v-img src="./assets/img 6.jpg" width="350" height="350" class="mt-5"> 
      </v-img>
    </v-col>

    <v-col
      cols="6"
      sm="4"
    >
      <v-img src="./assets/img 7.jpg" width="350" height="350" class="mt-5"> 
      </v-img>
    </v-col>
  </v-row>
  </center>
    </v-img>

  <center>
    <v-card-text><h2>How useful was this post?</h2>
    <h3 class="sec-text">Click on a star to rate it!</h3></v-card-text>
    <v-rating
      v-model="rating"
      background-color="black lighten-3"
      color="black"
      large
    ></v-rating>
    <v-row

      justify="center"
    >
          <v-col
        cols="9"
        md="3"
      >
    <v-text-field
          label="Text"
          outlined
          width="200px" 
          height="100px"
        ></v-text-field>
        <v-btn
      class="mx-2"
      dark
      small
      color="black"
    >
      <v-card-text dark>SUBMIT
      </v-card-text>
      </v-btn>
    </v-col>
    </v-row>
    <v-card-text class="red--text"><h2>Testimonials</h2></v-card-text>
  </center>

<v-row class="mt-5">
<v-card
    class="mx-auto"
    color="#C7E1DD"
    dark
    max-width="400"
  >
    <v-card-title>
      <v-list-item class="grow">
        <v-list-item-avatar color="grey darken-3">
          <v-img
            class="elevation-6"
            alt=""
            src="./assets/img 10.jpg"
          ></v-img>
        </v-list-item-avatar>

        <v-list-item-content>
          <v-list-item-title class="black--text">Kim Min-kyu</v-list-item-title>
          <v-rating
          v-model="rating"
          background-color="black lighten-3"
          color="black"
          readonly
          size="15"
        ></v-rating>
        </v-list-item-content>
        <v-row
          align="center"
          justify="end"
        >
        </v-row>
      </v-list-item>
    </v-card-title>
    <center>
    <v-card-text>
      <h3 class="black--text">"Turns out semicolon-less style is easier and safer in TS because most gotcha edge cases are type invalid as well."</h3>
    </v-card-text>
    </center>
  </v-card>

  <v-card
    class="mx-auto"
    color="#C7E1DD"
    dark
    max-width="400"
  >
    <v-card-title>
      <v-list-item class="grow">
        <v-list-item-avatar color="grey darken-3">
          <v-img
            class="elevation-6"
            alt=""
            src="./assets/img 12.jpg"
          ></v-img>
        </v-list-item-avatar>

        <v-list-item-content>
          <v-list-item-title class="black--text">Kwon Soon-young</v-list-item-title>
          <v-rating
          v-model="rating"
          background-color="black lighten-3"
          color="black"
          readonly
          size="15"
        ></v-rating>
        </v-list-item-content>
        <v-row
          align="center"
          justify="end"
        >
        </v-row>
      </v-list-item>
    </v-card-title>
    <center>
    <v-card-text>
      <h3 class="black--text">"Turns out semicolon-less style is easier and safer in TS because most gotcha edge cases are type invalid as well."</h3>
    </v-card-text>
    </center>
  </v-card>
  
  <v-card
    class="mx-auto"
    color="#C7E1DD"
    dark
    max-width="400"
  >
    <v-card-title>
      <v-list-item class="grow">
        <v-list-item-avatar color="grey darken-3">
          <v-img
            class="elevation-6"
            alt=""
            src="./assets/img 11.jpg"
          ></v-img>
        </v-list-item-avatar>

        <v-list-item-content>
          <v-list-item-title class="black--text">Kim Mingyu</v-list-item-title>
          <v-rating
          v-model="rating"
          background-color="black lighten-3"
          color="black"
          readonly
          size="15"
        ></v-rating>
        </v-list-item-content>
        <v-row
          align="center"
          justify="end"
        >
        </v-row>
      </v-list-item>
    </v-card-title>
    <center>
    <v-card-text>
      <h3 class="black--text">"Turns out semicolon-less style is easier and safer in TS because most gotcha edge cases are type invalid as well."</h3>
    </v-card-text>
    </center>
  </v-card>
  </v-row>

      <!-- If using vue-router -->
      <router-view></router-view>
    
  </v-main>

<v-footer
    dark
    padless
    class="mt-10"
  >
    <v-card
      flat
      tile
      class="black--text text-center"
      color="#FEDCD2"
    >
      <v-card-text>
        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-4 black--text"
          icon
        >
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
      </v-card-text>

      <v-card-text class="black--text pt-0">
        Phasellus feugiat arcu sapien, et iaculis ipsum elementum sit amet. Mauris cursus commodo interdum. Praesent ut risus eget metus luctus accumsan id ultrices nunc. Sed at orci sed massa consectetur dignissim a sit amet dui. Duis commodo vitae velit et faucibus. Morbi vehicula lacinia malesuada. Nulla placerat augue vel ipsum ultrices, cursus iaculis dui sollicitudin. Vestibulum eu ipsum vel diam elementum tempor vel ut orci. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
      </v-card-text>

      <v-divider color="black"></v-divider>

      <v-card-text class="black--text">
        {{ new Date().getFullYear() }} — <strong>Strapchain</strong>
      </v-card-text>
    </v-card>
  </v-footer>

</v-app>
</template>

<script>
export default {
  name: 'App',

  data: () => ({
    //
  }),
};


</script>

<script>
  export default {
    data: () => ({
      icons: [
        'mdi-facebook',
        'mdi-twitter',
        'mdi-instagram',
      ],
    }),
  }
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Rozha+One&display=swap');
.text-tittle{
  font-family:'Rozha One' ;
}

.sec-text{
  font-weight:400;
}
</style>