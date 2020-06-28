<template>
  <v-layout row wrap>
    <v-flex xs4>
      <v-card>
        <v-card-title primary-title>
          <div>
            <div class="headline">
              Batman vs Superman
              <span class="gey--text">2016 . Science fiction film/Action fiction . 3h 3m</span>
            </div>
          </div>
        </v-card-title>
        <v-card-text>
          It's been nearly two years since Superman's (Henry Cavill) colossal battle with Zod (Michael Shannon) devastated the city of Metropolis. The loss of life and collateral damage..
        </v-card-text>
        <v-card-actions>
          <v-btn text color="purple">
            Rate this movie
          </v-btn>
          <v-spacer></v-spacer>
        </v-card-actions>
      </v-card>
    </v-flex>
    <v-flex xs4>
      <v-card>
        <v-card-title primary-title>
          <div>
            <div class="headline">
              Logan 
              <span class="grey--text">2017 . Drama/Science fiction film . 2h 21m</span>
            </div>
          </div>
        </v-card-title>
        <v-card-text>
          iIn the near future, a weary Logan (Hugh Jackman) cares for an ailing Professor X (Patrick Stewart) at a remote outpost on the Mexican border. His plan to hide from the ouside world get upended when he meets a young woman ...
        </v-card-text>
        <v-card-actions>
          <v-btn text color="purple">
            Rate this movie
          </v-btn>
          <v-spacer></v-spacer>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>

export default {
  name: 'Home',
  components: {
  },
  data() {
    return {
      message: 'Hello there, how are you this morning?'
    }
  },
  methods: {
    reply() {
      this.message = "I'm doing great. Thank You!";
    }
  }
}
</script>
