<template>
  <div>
    <div style="position:relative;">
      <v-img eager src="/herobg-min.jpg" style="max-height:calc(100vh - 100px)">
        <v-container>
          <v-row>
            <v-col cols="12" md="12" class="text-center mx-auto">
              <div
                class="hero-title text-h2 font-weight-bold white--text mt-16 pt-16"
              >
                Find a home <br />
                where you can relax
              </div>
              <div class="hero-desc mt-6 white--text">
                Search house for rent. Get Results from 6 Engines at Once.
                Information 24/7.
                <br />
                Web,Images & Video. Trusted by Millions.
              </div>
            </v-col>
          </v-row>
        </v-container>
      </v-img>
      <v-card
        elevation="2"
        class="mt-6 d-flex justify-center align-center white rounded-lg px-10 py-4"
        style="position:absolute;bottom:-50px;width:max-content;left:0;right:0;margin-left:auto;margin-right:auto;"
      >
        <div class="text-left">
          <span class="text-h6 mr-2"
            >Location
            <v-icon class="black--text">keyboard_arrow_down</v-icon>
          </span>
          <br />
          <span class="grey--text mt-2">
            Florida
          </span>
        </div>
        <v-divider vertical inset class="mx-4"></v-divider>
        <div class="text-left">
          <span class="text-h6 mr-2"
            >Property Type
            <v-icon class="black--text">keyboard_arrow_down</v-icon>
          </span>
          <br />
          <span class="grey--text mt-2">
            Duplex
          </span>
        </div>
        <v-divider vertical inset class="mx-4"></v-divider>
        <div class="text-left">
          <span class="text-h6 mr-2"
            >Max budget
            <v-icon class="black--text">keyboard_arrow_down</v-icon>
          </span>
          <br />
          <span class="grey--text mt-2">
            $2500
          </span>
        </div>
        <span class="mr-4"></span>
        <v-btn
          icon
          style="background-color:#263238"
          x-large
          class="rounded-lg ma-0 pa-0"
          width="70"
          height="70"
        >
          <v-icon class="white--text">fal fa-search</v-icon>
        </v-btn>
      </v-card>
    </div>
    <v-container class="my-16 py-16">
      <v-row>
        <v-col cols="12" md="12">
          <div class="text-h3 font-weight-bold text-center mb-5">
            Advantages of Reno
          </div>
        </v-col>
        <v-col cols="12" md="4" v-for="i in advantage" :key="i">
          <v-hover v-slot="{ hover }">
            <v-card
              height="300"
              class="rounded-lg d-flex align-center"
              :elevation="hover ? '5' : '0'"
            >
              <div>
                <v-card-title class="d-flex justify-center">
                  <v-icon
                    x-large
                    class="white--text primary pa-5 rounded-circle"
                  >
                    {{ i.icon }}
                  </v-icon>
                </v-card-title>
                <v-card-title class="d-flex justify-center pb-0">
                  {{ i.title }}
                </v-card-title>
                <v-card-text class="text-center">
                  {{ i.desc }}
                </v-card-text>
              </div>
            </v-card>
          </v-hover>
        </v-col>
      </v-row>
    </v-container>
    <div style="background-color:#F4FCFF;">
      <v-container class="mt-0">
        <v-row class="d-flex align-center mt-16">
          <v-col cols="12" md="6">
            <div
              class="text-h2 font-weight-black mb-10"
              style="line-height:1.2em;"
            >
              Live happliy,<br />
              Reno helps you for<br />
              finding home
            </div>
            <div class="mb-4">
              Properties To rent. Find rental property listed<br />
              directly from private landlords and letting agents<br />
              from all over.
            </div>
            <div class="mb-10">
              Search House For Rent. Get results from<br />
              6 Engines at Once. Information 24/7. Web,<br />
              Images & Video. Trusted by Millions.
            </div>
            <v-btn outlined>Explore more</v-btn>
          </v-col>
          <v-col cols="12" md="6">
            <div style="position:relative;">
              <div
                class="accent"
                style="position:absolute;top:-50px;left:-50px;width:200px;height:200px;border-radius:100px;"
              ></div>
              <div
                class="accent"
                style="position:absolute;bottom:-40px;right:-40px;width:200px;height:200px;border-radius:100px;"
              ></div>
              <v-img eager class="rounded-lg" src="/hide.jpg"></v-img>
            </div>
          </v-col>
        </v-row>
      </v-container>
    </div>
    <!-- waves -->
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
      <path
        fill="#F4FCFF"
        fill-opacity="1"
        d="M0,0L34.3,21.3C68.6,43,137,85,206,112C274.3,139,343,149,411,144C480,139,549,117,617,133.3C685.7,149,754,203,823,197.3C891.4,192,960,128,1029,128C1097.1,128,1166,192,1234,229.3C1302.9,267,1371,277,1406,282.7L1440,288L1440,0L1405.7,0C1371.4,0,1303,0,1234,0C1165.7,0,1097,0,1029,0C960,0,891,0,823,0C754.3,0,686,0,617,0C548.6,0,480,0,411,0C342.9,0,274,0,206,0C137.1,0,69,0,34,0L0,0Z"
      ></path>
    </svg>
    <!-- waves -->
    <v-container class="pb-16">
      <v-row>
        <v-col cols="12" md="12">
          <div class="text-center text-h3 font-weight-bold">
            How Reno works
          </div>
          <div class="text-center mt-5 mb-10" style="font-size:20px;">
            Properties To rent. Find rental property listed<br />
            directly from private landlords and letting agents<br />
            from all over.
          </div>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" md="4">
          <ul class="how-work">
            <li
              class="font-weight-black"
              v-for="(how, i) in hows"
              :key="how.id"
            >
              <span>{{ i + 1 }}</span
              >{{ how.title }}
            </li>
          </ul>
        </v-col>
        <v-col cols="12" md="8">
          <div style="position:relative;">
            <v-img
              eager
              class="rounded-lg"
              height="500"
              src="/email.jpg"
            ></v-img>
            <div
              style="position:absolute;background-color:#222E3C;font-sizbottom:0px;"
            ></div>
            <div
              class="white--text font-weight-light"
              style="line-height:1.3em;padding:30px 50px;display:flex;align-items:center;position:absolute;bottom:-50px;left:-50px;font-size:30px;background-color:#222E3C;"
            >
              Find rental property listed directly <br />
              landlords and letting agents from all over.
              <!-- Explore all <br />your needs at <br />a glance -->
            </div>
          </div>
        </v-col>
      </v-row>
    </v-container>
    <div style="background-color:#F4FCFF;">
      <v-container class="py-16">
        <v-row>
          <v-col cols="12" md="6" class="d-flex">
            <v-spacer></v-spacer>
            <v-img
              eager
              class="rounded-lg"
              height="500"
              width="300"
              src="https://image.freepik.com/free-photo/smiling-young-man-standing-holding-tablet-computer_1262-18710.jpg"
            ></v-img>
            <v-spacer></v-spacer>
          </v-col>
          <v-col cols="12" md="6">
            <div class="text-h4">
              Reno made my life easy.<br />
              It helped me with the search<br />
              form my first ever investment.<br />
              They were an absolute pleasure<br />
              to work with from the<br />
              beginning to completion.<br />
              Thanks to the team.
            </div>
            <div>
              <v-card-title class="px-0 pb-0">
                Afrafat H.
              </v-card-title>
              <v-card-text class="pl-0">
                Boston, UK
              </v-card-text>
              <div class="d-flex align-center">
                <v-rating
                  v-model="rating"
                  class="pa-0"
                  dense
                  readonly
                  background-color="orange lighten-3"
                  color="orange"
                  large
                ></v-rating>
                <v-spacer></v-spacer>
                <v-btn text>
                  <v-icon>fal fa-arrow-left</v-icon>
                </v-btn>
                <v-btn text x-large>
                  <v-icon x-large>fal fa-arrow-right</v-icon>
                </v-btn>
              </div>
            </div>
          </v-col>
        </v-row>
      </v-container>
    </div>
    <v-container class="my-10">
      <v-row>
        <v-col cols="12" md="12" class="d-flex mx-auto">
          <v-card flat class="rounded-0 ma-0 pa-0">
            <v-img
              eager
              height="500"
              class="rounded-lg d-flex align-center justify-center"
              src="/email-min.jpg"
            >
              <v-btn
                icon
                color="white"
                x-large
                class="d-flex mx-auto"
                style="background-color:white;box-shadow: 0px 0px 0px 15px #ffffffaa;"
              >
                <v-icon color="black" small>fas fa-play</v-icon>
              </v-btn>
            </v-img>
            <div
              class="white--text font-weight-light"
              style="line-height:1.3em;padding:100px 100px;display:flex;align-items:center;position:absolute;bottom:-50px;right:-50px;font-size:40px;background-color:#222E3C;"
            >
              Explore all <br />your needs at <br />a glance
            </div>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
    <v-container class="mt-16">
      <v-img
        eager
        height="200"
        class="rounded-lg d-flex align-center justify-center"
        src="/email-min.jpg"
      >
        <v-overlay absolute>
          <v-row>
            <v-col
              cols="12"
              md="6"
              class="mx-10 d-flex mx-auto text-h3 font-weight-black"
            >
              <div class="white--text" style="width:450px;">
                Ready to find your new place ?
              </div>
            </v-col>
            <v-col cols="12" md="6" class="d-flex align-center justify-center">
              <div class="email">
                <input
                  type="text"
                  name="email"
                  id="emailaddress"
                  placeholder="Email address"
                />
                <button>Send</button>
              </div>
            </v-col>
          </v-row>
        </v-overlay>
      </v-img>
    </v-container>
  </div>
</template>

<script>
export default {
  data() {
    return {
      rating: "5",
      hows: [
        {
          id: "0",
          title: "Search"
        },
        {
          id: "1",
          title: "Choose"
        },
        {
          id: "2",
          title: "Contact"
        },
        {
          id: "3",
          title: "Book"
        }
      ],
      advantage: [
        {
          id: "1",
          icon: "fal fa-home",
          title: "Property Insurance",
          desc:
            "No longer have to negotiate commissioins and haggle with other agents"
        },
        {
          id: "2",
          icon: "fal fa-badge-percent",
          title: "Lowest Commission",
          desc:
            "No longer have to negotiate commissioins and haggle with other agents"
        },
        {
          id: "3",
          icon: "fal fa-user",
          title: "Tax Advantage",
          desc:
            "No longer have to negotiate commissioins and haggle with other agents"
        }
      ]
    };
  }
};
</script>
<style lang="scss">
ul.how-work {
  list-style: none;
  padding: 0px;
  li {
    font-size: 30px;
    line-height: 3em;
    span {
      color: white;
      background-color: #222e3c;
      padding: 10px 20px;
      border-radius: 100%;
      margin-right: 20px;
    }
  }
}
div.hero-desc {
  font-family: "Varela Round", sans-serif;
  font-size: 20px;
}
div.email {
  display: flex;
  align-items: center;
  height: min-content;
  background: white;
  border-radius: 10px;
  input {
    height: 40px;
    // width: 100px;
    margin-left: 10px;
    border-radius: 0px;
    &:focus-visible {
      outline: 0px;
      border-radius: 0px;
    }
  }
  button {
    width: 130px;
    height: 40px;
    margin: 5px;
    border-radius: 10px;
    background: #222e3c;
    color: white;
  }
}
</style>
