<template>
  <q-page class="flex container backGroundRoadmap flex-center">
    <q-header class="bg-transparent">
      <q-toolbar class="text-black gt-lg  absolute fixed toolbar">
        <q-btn style="margin-left: 10em; top: 0.8em;" flat class=" q-mr-sm q-mt-sm" to="/">

          <q-img width="80px"
            src="https://cdn.discordapp.com/attachments/1034844300867031232/1035340897455456306/DD_Logo_transparent.png">
          </q-img>
        </q-btn>
        <q-toolbar-title class="textNeue q-mt-md text-bold text-white q-ml-xs">
        </q-toolbar-title>
        <div style="margin-top: 1em; margin-right: -0.5em" class=" q-mt-sm q-pt-md q-gutter-none">
          <q-btn to="/roadmap" style="margin-right: -1.5em " class="textFjala qbtnn text-subtitle text-bold" flat
            color="white" text-color="white" label="Mission">
          </q-btn>
          <q-btn to="/team" style="margin-right: 1em " class="textFjala qbtnn text-subtitle text-bold" flat
            color="white" text-color="white" label="Team">
          </q-btn>
          <!-- <q-btn target="_blank" href="https://deadsouls-staking.web.app/" style="margin-right: -1.2em"
            class="textFjala qbtnn text-subtitle text-bold" flat color="white" text-color="white" label="STAKING">
          </q-btn>
          <q-btn target="_blank" href="https://raffle-dsd.vercel.app/" class="textFjala qbtnn text-subtitle text-bold"
            flat color="white" text-color="white" label="RAFFLES">
          </q-btn> -->
        </div>
        <div style="margin-right: 10em; margin-top: 0.6em " class="q-gutter-xs">
          <q-btn target="_blank" href="https://twitter.com/_Dead_Degens" round flat size="0.50em"
            class="bg-transparent button-social" color="white">
            <q-icon size="2.5em" name="fa-brands fa-twitter"></q-icon>
          </q-btn>
          <q-btn target="_blank" href="https://discord.gg/" round flat style="margin-right: 0.3em"
            size="0.50em" class="bg-transparent button-social q-px-md" color="white">
            <q-icon size="2.5em" name="fa-brands fa-discord"></q-icon>
          </q-btn>
          <q-btn target="_blank" href="https://magiceden.io/" round flat style="margin-top: 1.4em"
            size="0.35em" class="bg-transparent button-social" color="black">
            <q-avatar size="7.5em">
              <img src="https://cdn.discordapp.com/attachments/971074716406284289/985484686908350484/wwwwwwwwwww.png" />
            </q-avatar>
          </q-btn>
        </div>

      </q-toolbar>


      <q-toolbar class="text-black gt-md lt-xl  absolute fixed toolbar">
        <q-btn flat style="margin-left: 10em; top: 0.8em;" class="q-mr-sm q-mt-sm" to="/">
          <q-img width="80px"
            src="https://cdn.discordapp.com/attachments/1034844300867031232/1035340897455456306/DD_Logo_transparent.png">
          </q-img>
        </q-btn>
        <q-toolbar-title class="textNeue q-mt-md text-bold text-white q-ml-xs">
        </q-toolbar-title>
        <div style="margin-top: 0.9em; margin-right: 0.5em" class=" q-mt-sm q-pt-md button-md">
          <q-btn to="/roadmap" style="margin-right: -1.5em " class="textFjala qbtnn text-subtitle text-bold" flat
            color="black" text-color="white" label="Mission">
          </q-btn>
          <q-btn to="/team" style="margin-right: -1.5em " class="textFjala qbtnn text-subtitle text-bold" flat
            color="black" text-color="white" label="Team">
          </q-btn>
        </div>
        <div style="margin-left: -0.5em; margin-top: 0.45em" class="q-gutter-xs button-div-lg">
          <q-btn target="_blank" href="https://twitter.com/_Dead_Degens" round flat size="0.50em"
            class="bg-transparent button-social q-px-md" color="black">
            <q-icon color="white" size="2.5em" name="fa-brands fa-twitter"></q-icon>
          </q-btn>
          <q-btn round flat size="0.50em" class="bg-transparent button-social q-px-md" color="black">
            <q-icon size="2.5em" color="white" name="fa-brands fa-discord"></q-icon>
          </q-btn>
          <q-btn round flat style="margin-top: 2.3em" size="0.30em" class="bg-transparent button-social" color="black">
            <q-avatar size="8em">
              <img src="https://cdn.discordapp.com/attachments/971074716406284289/985484686908350484/wwwwwwwwwww.png" />
            </q-avatar>
          </q-btn>
        </div>

      </q-toolbar>

      <q-toolbar class="text-black gt-sm lt-lg  absolute fixed toolbar">
        <q-btn flat style="margin-left: 10em; !important;" class="button-icon q-mr-sm q-mt-md" dense round to="/">
          <q-img width="75px"
            src="https://cdn.discordapp.com/attachments/1034844300867031232/1035340897455456306/DD_Logo_transparent.png">
          </q-img>
        </q-btn>
        <q-toolbar-title class="textNeue q-mt-md text-bold text-white q-ml-xs">
        </q-toolbar-title>
        <div style="margin-top: 0.8em; margin-right: -0.5em;" class=" q-mt-sm q-pt-md button">
          <q-btn to="/roadmap" style="margin-right: -1.5em " class="textFjala qbtnn text-subtitle text-bold" flat
            color="black" text-color="white" label="Mission">
          </q-btn>
          <q-btn to="/team" style="margin-right: -1.5em " class="textFjala qbtnn text-subtitle text-bold" flat
            color="black" text-color="white" label="Team">
          </q-btn>
        </div>
        <div style="margin-left: 0.4em ; margin-right: 5em; margin-top: 0.5em" class="q-gutter-xs button-div">
          <q-btn target="_blank" href="https://twitter.com/_Dead_Degens" round flat size="0.50em"
            class="bg-transparent button-social q-px-md" color="white">
            <q-icon size="2.5em" name="fa-brands fa-twitter"></q-icon>
          </q-btn>
          <q-btn round flat size="0.50em" class="bg-transparent button-social q-px-md" color="white">
            <q-icon size="2.5em" name="fa-brands fa-discord"></q-icon>
          </q-btn>
          <q-btn round flat style="margin-top: 3.2em" size="0.25em" class="bg-transparent button-social" color="black">
            <q-avatar size="11em">
              <img src="https://cdn.discordapp.com/attachments/971074716406284289/985484686908350484/wwwwwwwwwww.png" />
            </q-avatar>
          </q-btn>
        </div>

      </q-toolbar>

      <q-toolbar class="text-black lt-md  absolute fixed toolbar">

        <q-btn flat style="margin-left: 2em; !important ; padding-top: 0.4em !important"
          class="button-icon q-mr-sm q-mt-sm" dense round to="/">
          <q-img width="80px"
            src="https://cdn.discordapp.com/attachments/1034844300867031232/1035340897455456306/DD_Logo_transparent.png">
          </q-img>
        </q-btn>

        <q-toolbar-title class="textNeue q-mt-md text-bold text-white q-ml-xs">
        </q-toolbar-title>

        <q-btn-dropdown dense class="textFjala bg-purple text-subtitle lt-md"
          style="margin-top: 2em; margin-right: 2em; width: 45px;" text-color="black" color="white"
          dropdown-icon="menu">
          <q-list class="">
            <q-item to="/roadmap" clickable v-close-popup @click="onItemClick">
              <q-item-section>
                <span class="textFjala">MISSION</span>
              </q-item-section>
            </q-item>

            <q-item to="/team" clickable v-close-popup @click="onItemClick">
              <q-item-section>
                <span class="textFjala">TEAM</span>
              </q-item-section>
            </q-item>


          </q-list>
        </q-btn-dropdown>


      </q-toolbar>
    </q-header>
    <!-- <div class="q-gutter-md flex flex-center absolute ">
      <q-card style="opacity: 0.95;" class="my-card bg-transparent" flat bordered>
        <q-card-section class="bgyellow" horizontal>
          <q-card-section class="text-black textKdam ">
            <h5 class="  q-py-xs q-ma-none">Punk</h5>
            A Passionate community builder
            with high ambitions
            to bring ideas to life
            on the Solana Blockchain.
            Studied of Computer Science.

          </q-card-section>

          <q-img style="border-radius: 6px" class="col-7 "
            src="https://cdn.discordapp.com/attachments/459557016042471454/985771984694698045/104-2.png" />


        </q-card-section>

        <q-card-section class="bgyellow" horizontal>
          <q-card-actions horizontal class="justify-around">
            <q-btn flat round class="inset-shadow" color="black" icon="fa-brands fa-twitter" />
            <q-btn flat round class="inset-shadow" color="black" icon="fa-brands fa-discord" />
          </q-card-actions>
        </q-card-section>

      </q-card>

      <q-card style="opacity: 0.95;" class="my-card bg-transparent" flat bordered>
        <q-card-section class="bggrey" horizontal>
          <q-card-section class="text-black textKdam">
            <h5 class="q-py-xs q-ma-none">Punk</h5>
            A Passionate community builder
            with high ambitions
            to bring ideas to life
            on the Solana Blockchain.
            Studied of Computer Science.

          </q-card-section>

          <q-img style="border-radius: 5px" class="col-7 shadow-14 rounded-borders"
            src="https://cdn.discordapp.com/attachments/459557016042471454/985778441632743434/123-1.png" />


        </q-card-section>

        <q-card-section  class="bggrey" horizontal>
          <q-card-actions horizontal class="justify-around">
          <q-btn flat round class="inset-shadow" color="black" icon="fa-brands fa-twitter" />
            <q-btn flat round class="inset-shadow" color="black" icon="fa-brands fa-discord" />
          </q-card-actions>
        </q-card-section>

      </q-card>

      <q-card style="opacity: 0.95;" class="my-card bg-transparent" flat bordered>
        <q-card-section class="bgblue" horizontal>
          <q-card-section class="text-black textKdam">
            <h5 class="q-py-xs q-ma-none">Punk</h5>
            A Passionate community builder
            with high ambitions
            to bring ideas to life
            on the Solana Blockchain.
            Studied of Computer Science.

          </q-card-section>

          <q-img style="border-radius: 5px" class="col-7 shadow-14 rounded-borders"
            src="https://cdn.discordapp.com/attachments/459557016042471454/985771984984113152/161.png" />


        </q-card-section>

        <q-card-section class="bgblue" horizontal>
          <q-card-actions horizontal class="justify-around">
            <q-btn flat round class="inset-shadow" color="black" icon="fa-brands fa-twitter" />
            <q-btn flat round class="inset-shadow" color="black" icon="fa-brands fa-discord" />
          </q-card-actions>
        </q-card-section>

      </q-card>


    </div> -->

    <!-- XL SIZE -->
    <div style="padding-top: 4em;" class="gt-lg q-gutter-md flex flex-center absolute ">
      <h2 style="margin-top: -3.7em; opacity: 0.75;" class="text-center text-white text-bold absolute-center  textKdam">
        Our Plan</h2>
      <q-card class="my-card-xl text-white"
        style="background: radial-gradient(circle, #0D004D 10%, #09001A 100%); opacity: 0.7; border-radius: 25px">
        <q-card-section>
          <div class="text-h5 textKdam text-bold ">Stage 1</div>
        </q-card-section>

        <q-card-section style="font-size: 0.95rem" class="q-pt-md  qp-pb-md textKdam">
          <!-- • Rarity Chart Implementation <br>
          • Listing to Magic Eden <br>
          • Matrica verification for DAO Benefits <br>
          • $SOUL Token Introduced <br>
          • List $SOUL on platforms to exchange (Sell/Buy) <br> -->
          • Lorem ipsum dolor sit amet, <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
        </q-card-section>

      </q-card>
      <q-card class="my-card-xl text-white"
        style="background: radial-gradient(circle, #0D004D 10%, #09001A 100%); opacity: 0.7; border-radius: 25px">
        <q-card-section>
          <div class="text-h5 textKdam  text-bold">Stage 2</div>
        </q-card-section>

        <q-card-section style="font-size: 0.94rem" class="q-pt-md qp-pb-md textKdam">
          • Lorem ipsum dolor sit amet, <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>

        </q-card-section>

      </q-card>

      <q-card class="my-card-xl text-white"
        style="background: radial-gradient(circle, #0D004D 10%, #09001A 100%); opacity: 0.7; border-radius: 25px">
        <q-card-section>
          <div class="text-h5 textKdam  text-bold">Stage 3</div>
        </q-card-section>

        <q-card-section style="font-size: 0.94rem" class="q-pt-md textKdam">
          • Lorem ipsum dolor sit amet, <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
        </q-card-section>
      </q-card>
    </div>

    <!-- LG SIZE -->
    <div style="margin-top: 6em" class="gt-md lt-xl q-gutter-md flex flex-center absolute ">

      <q-card class="my-card-lg text-white"
        style="background: radial-gradient(circle, #0D004D 10%, #09001A 100%); opacity: 0.7; border-radius: 25px">
        <q-card-section>
          <div class="text-h5 text-bold textKdam">Stage 1</div>
        </q-card-section>

        <q-card-section style="font-size: 1rem" class="q-pt-md qp-pb-md textKdam">
          • Lorem ipsum dolor sit amet, <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
        </q-card-section>
      </q-card>
      <q-card class="my-card-lg text-white"
        style="background: radial-gradient(circle, #0D004D 10%, #09001A 100%); opacity: 0.7; border-radius: 25px">
        <q-card-section>
          <div class="text-h5 textKdam text-bold">Stage 2</div>
        </q-card-section>

        <q-card-section style="font-size: 0.85rem" class="q-pt-md qp-pb-md textKdam">
          • Lorem ipsum dolor sit amet, <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>

        </q-card-section>
      </q-card>

      <q-card class="my-card-lg text-white"
        style="background: radial-gradient(circle, #0D004D 10%, #09001A 100%); opacity: 0.7; border-radius: 25px">
        <q-card-section>
          <div class="text-h5 textKdam text-bold">Stage 3</div>
        </q-card-section>

        <q-card-section style="font-size: 0.90rem" class="q-pt-md textKdam">
          • Lorem ipsum dolor sit amet, <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
        </q-card-section>
      </q-card>
    </div>

    <!-- MD SIZE -->
    <div style="margin-top: 6em" class="gt-sm lt-lg q-gutter-md flex flex-center absolute ">

      <q-card class="my-card-md text-white"
        style="background: radial-gradient(circle, #0D004D 10%, #09001A 100%); opacity: 0.7; border-radius: 25px">
        <q-card-section>
          <div class="text-h5 text-bold textKdam">Stage 1</div>
        </q-card-section>

        <q-card-section style="font-size: 0.85rem" class="q-pt-md qp-pb-md textKdam text-bold">
          • Lorem ipsum dolor sit amet, <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
        </q-card-section>
      </q-card>
      <q-card class="my-card-md text-white"
        style="background: radial-gradient(circle, #0D004D 10%, #09001A 100%); opacity: 0.7; border-radius: 25px">
        <q-card-section>
          <div class="text-h5 textKdam text-bold">Stage 2</div>
        </q-card-section>

        <q-card-section style="font-size: 0.70rem" class="q-pt-md qp-pb-md textKdam text-bold">
          • Lorem ipsum dolor sit amet, <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>

        </q-card-section>
      </q-card>

      <q-card class="my-card-md text-white"
        style="background: radial-gradient(circle, #0D004D 10%, #09001A 100%); opacity: 0.7; border-radius: 25px">
        <q-card-section>
          <div class="text-h5 textKdam text-bold">Stage 3</div>
        </q-card-section>

        <q-card-section style="font-size: 0.75rem" class="q-pt-md textKdam text-bold">
          • Lorem ipsum dolor sit amet, <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
          • saepe, itaque rem odit quos <br>
          • saepe, itaque rem odit quos <br>
          • consectetur adipisicing elit. Ad debitis voluptas <br>
        </q-card-section>
      </q-card>
    </div>

    <!-- SM SIZE -->
    <div style="padding-top: 10em; padding-bottom: 8em" class="flex flex-center q-ma-md  q-pa-md lt-md col q-gutter-md">
      <q-card style="border-radius: 10px; width: 80vw;" class="roadmap-mob col-1 q-mb-xl bg-transparent" flat bordered>

        <q-card-section style="opacity: 0.9" class="bg-black">
          <div class="text-h4 textKdam text-white">Stage 1</div>
          <div class="text-subtitle2 text-white textFjala q-mt-sm q-mb-xs">
            • Rarity Chart Implementation <br>
            • Listing to Magic Eden <br>
            • Matrica verification for DAO Benefits <br>
            • $SOUL Token Introduced <br>
            • List $SOUL on platforms to exchange (Sell/Buy) <br>
          </div>
        </q-card-section>
      </q-card>

      <q-card style="border-radius: 10px" class="roadmap-mob col-2 q-mb-xl bg-transparent" flat bordered>

        <q-card-section style="opacity: 0.9; width: 80vw;" class="bg-black">
          <div class="text-h4 textKdam text-white">Stage 2</div>
          <div class="text-subtitle2 text-white textFjala q-mt-sm q-mb-xs">
            • Lorem ipsum dolor sit amet, <br>
            • consectetur adipisicing elit. Ad debitis voluptas <br>
            • saepe, itaque rem odit quos <br>
            • consectetur adipisicing elit. Ad debitis voluptas <br>
            • saepe, itaque rem odit quos <br>
            • saepe, itaque rem odit quos <br>
            • consectetur adipisicing elit. Ad debitis voluptas <br>
          </div>
        </q-card-section>
      </q-card>
      <q-card style="border-radius: 10px" class="roadmap-mob col-3 q-mb-xl bg-transparent" flat bordered>

        <q-card-section style="opacity: 0.9; width: 80vw; " class="bg-black">
          <div class="text-h4 textKdam text-white">Stage 3</div>
          <div class="text-subtitle2 text-white textFjala q-mt-sm q-mb-xs">
            • Lorem ipsum dolor sit amet, <br>
            • consectetur adipisicing elit. Ad debitis voluptas <br>
            • saepe, itaque rem odit quos <br>
            • consectetur adipisicing elit. Ad debitis voluptas <br>
            • saepe, itaque rem odit quos <br>
            • saepe, itaque rem odit quos <br>
            • consectetur adipisicing elit. Ad debitis voluptas <br>
          </div>
        </q-card-section>
      </q-card>

    </div>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Roadmap',
  setup() {

  }
})


</script>

<style >
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Kdam+Thmor+Pro&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@100;300;400&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Fjalla+One&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Fascinate&display=swap');


.my-card-xl {
  transition-duration: 1s;
  width: 24vw;
  height: 40vh;
}

.my-card-lg {
  transition-duration: 1s;
  width: 23vw;
  height: 60vh;
}

.my-card-md {
  transition-duration: 1s;
  width: 25vw;
  height: 55vh;
}

.my-card-sm {
  max-width: 10vw;
  height: 20vh;
}

.text-card {
  width: 10vw;
  height: 50vh;
}

.roadmap-mob {
  max-width: 20vw;
  max-height: 20vh;
}


.textJap {
  font-family: 'Noto Sans KR', sans-serif;
}

.textNeue {
  font-family: 'Bebas Neue', cursive;
}

.textFjala {
  font-family: 'Fjalla One', sans-serif;
  letter-spacing: 0.18rem;
}

.textKdam {
  font-family: 'Kdam Thmor Pro', sans-serif;
}

.backGroundRoadmap {
  background-image: url('https://cdn.discordapp.com/attachments/459557016042471454/1042555183399456869/digital-art-artwork-interior-room-1457511-wallhere.com.jpg');
  background-position: 0;
  background-size: cover;
}

.button-div {
  margin-right: 8.9em;
}

.button-div-md {
  margin-right: 0.9em;
}

.button-div-lg {
  margin-right: 6em;
}


.button-div-sm {
  margin-right: 8.9em;
}

.button-icon-lg {
  top: 0.6em;
  margin-left: 8em;
}


.button-icon {
  top: 0.6em;
  margin-left: 8.5em;
}

.qbtnn {
  border-radius: 5px;
  height: 2.1em;
  width: 7.2em;
}

.button {
  margin-right: 1.5vh;
}

.button-md {
  margin-right: 1.5vh;
}

.button-social {
  padding: 1.5em;
  text-align: center;
  margin-right: 1em;
  top: 1.1em;

}

.toolbar {
  display: flex;
  top: 0;
}
</style>
