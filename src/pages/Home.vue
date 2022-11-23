<template>
  <q-page class="flex backGround flex-center">
    <q-header class="bg-transparent">
      <q-toolbar class="text-black gt-lg  absolute fixed toolbar">
        <q-btn style="margin-left: 10em; top: 0.8em;" flat class=" q-mr-sm q-mt-sm" to="/">

          <q-img width="80px"
            src="https://cdn.discordapp.com/attachments/1034844300867031232/1035340897455456306/DD_Logo_transparent.png">
          </q-img>
        </q-btn>
        <q-toolbar-title class="textNeue q-mt-md text-bold text-white q-ml-xs">
        </q-toolbar-title>
        <div style="margin-top: 1em; margin-right: 1em" class=" q-mt-sm q-pt-md q-gutter-none">
          <q-btn to="/roadmap" style="margin-right: -1.5em " class="textFjala qbtnn text-subtitle text-bold" flat
            color="white" text-color="white" label="Mission">
          </q-btn>
          <q-btn to="/team" style="margin-right: -1.5em " class="textFjala qbtnn text-subtitle text-bold" flat
            color="white" text-color="white" label="Team">
          </q-btn>
          <!-- <q-btn target="_blank" href="https://deadsouls-staking.web.app/" style="margin-right: -1.2em" class="textFjala qbtnn text-subtitle text-bold" flat
            color="white" text-color="white" label="STAKING">
          </q-btn>
          <q-btn target="_blank" href="https://raffle-dsd.vercel.app/" class="textFjala qbtnn text-subtitle text-bold" flat color="white" text-color="white"
            label="RAFFLES">
          </q-btn> -->
        </div>
        <div style="margin-right: 10em; margin-top: 0.6em " class="q-gutter-xs">
          <q-btn target="_blank" href="https://discord.gg/" round flat style="margin-right: 0.3em" size="0.50em"
            class="bg-transparent button-social q-px-md" color="white">
            <q-icon size="2.5em" name="fa-brands fa-discord"></q-icon>
          </q-btn>
          <q-btn style="margin-right: -0.2em" target="_blank" href="https://twitter.com/_Dead_Degens" round flat
            size="0.50em" class="bg-transparent button-social" color="white">
            <q-icon size="2.5em" name="fa-brands fa-twitter"></q-icon>
          </q-btn>
          <q-btn target="_blank" href="https://magiceden.io/" round flat style="margin-top: 1.4em"
            size="0.35em" class="bg-transparent button-social" color="black">
            <q-avatar size="7.5em">
              <img src="https://cdn.discordapp.com/attachments/971074716406284289/985484686908350484/wwwwwwwwwww.png" />
            </q-avatar>
          </q-btn>
          <q-btn style="margin-top: -0.4em; margin-left: -1.5em;" onclick="document.getElementById('player').play()"
            v-if="play == 1" @click="() => { play = 2; }" round flat size="0.7em" class="bg-transparent button-social"
            color="white">
            <q-icon name="play_arrow" size="2.4em" />
          </q-btn>
          <audio id="player" style="opacity: 0.5;"
            src="https://cdn.discordapp.com/attachments/971074716406284289/987255919291273287/Dead_Souls.mp3">
          </audio>
          <q-btn style="margin-top: -0.4em; margin-left: -1.5em;" onclick="document.getElementById('player').pause()"
            v-if="play == 2" @click="() => { play = 1; }" round flat size="0.7em" class="bg-transparent button-social"
            color="white">
            <q-icon name="pause" size="2.4em" />
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
          <q-btn target="_blank" href="https://deadsouls-staking.web.app/" style="margin-right: -1.5em " class="textFjala qbtnn text-subtitle text-bold" flat
            color="black" text-color="white" label="STAKING">
          </q-btn>
          <q-btn target="_blank" href="https://raffle-dsd.vercel.app/" class="textFjala qbtnn text-subtitle text-bold" flat color="black" text-color="white"
            label="RAFFLES">
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
          <q-btn style="margin-top: -0.4em; margin-left: -1.3em;" onclick="document.getElementById('player').play()"
            v-if="play == 1" @click="() => { play = 2; }" round flat size="0.7em" class="bg-transparent button-social"
            color="white">
            <q-icon name="play_arrow" size="2.4em" />
          </q-btn>
          <audio id="player" style="opacity: 0.5;"
            src="https://cdn.discordapp.com/attachments/971074716406284289/987255919291273287/Dead_Souls.mp3">
          </audio>
          <q-btn style="margin-top: -0.4em; margin-left: -1.3em;" onclick="document.getElementById('player').pause()"
            v-if="play == 2" @click="() => { play = 1; }" round flat size="0.7em" class="bg-transparent button-social"
            color="white">
            <q-icon name="pause" size="2.4em" />
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
          <q-btn target="_blank" href="https://deadsouls-staking.web.app/" style="margin-right: -1.5em " class="textFjala qbtnn text-subtitle text-bold" flat
            color="black" text-color="white" label="STAKING">
          </q-btn>
          <q-btn target="_blank" href="https://raffle-dsd.vercel.app/" class="textFjala qbtnn text-subtitle text-bold" flat color="black" text-color="white"
            label="RAFFLES">
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
          <q-btn style="margin-top: -0.4em; margin-left: -1.3em;" onclick="document.getElementById('player').play()"
            v-if="play == 1" @click="() => { play = 2; }" round flat size="0.7em" class="bg-transparent button-social"
            color="white">
            <q-icon name="play_arrow" size="2.4em" />
          </q-btn>
          <audio id="player" style="opacity: 0.5;"
            src="https://cdn.discordapp.com/attachments/971074716406284289/987255919291273287/Dead_Souls.mp3">
          </audio>
          <q-btn style="margin-top: -0.4em; margin-left: -1.3em;" onclick="document.getElementById('player').pause()"
            v-if="play == 2" @click="() => { play = 1; }" round flat size="0.7em" class="bg-transparent button-social"
            color="white">
            <q-icon name="pause" size="2.4em" />
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

        <q-btn-dropdown dense class="textFjala bg-purple  text-subtitle lt-md"
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

            <q-item target="_blank" href="https://raffle-dsd.vercel.app/" clickable v-close-popup @click="onItemClick">
              <q-item-section >
                <span class="textFjala">RAFFLE</span>
              </q-item-section>
            </q-item>

            <q-item target="_blank" href="https://deadsouls-staking.web.app/"  clickable v-close-popup @click="onItemClick">
              <q-item-section >
                <span class="textFjala">STAKING</span>
              </q-item-section>
            </q-item>
            <q-separator />
            <q-item target="_blank" href="https://discord.gg/" clickable v-close-popup @click="onItemClick">
              <q-item-section>
                <span class="textFjala">DISCORD</span>
              </q-item-section>
            </q-item>

            <q-item target="_blank" href="https://twitter.com/_Dead_Degens" clickable v-close-popup
              @click="onItemClick">
              <q-item-section>
                <span class="textFjala">TWITTER</span>
              </q-item-section>
            </q-item>

            <q-item target="_blank" href="https://magiceden.io/" clickable v-close-popup
              @click="onItemClick">
              <q-item-section>
                <span class="textFjala">SECONDARY</span>
              </q-item-section>
            </q-item>


          </q-list>
        </q-btn-dropdown>


      </q-toolbar>
    </q-header>
    <div style="margin-top: -0.5em" class="gt-lg flex flex-center absolute-center">
      <!-- <img src="https://cdn.discordapp.com/attachments/971074716406284289/987329257137143859/v.png"> -->
    </div>





  </q-page>
</template>

<script>
import { defineComponent } from 'vue'
import { ref } from 'vue'

export default defineComponent({
  name: 'Home',
  setup() {
    return {
      play: ref(1)
    }
  }
})


</script>

<style >
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Kdam+Thmor+Pro&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@100;300;400&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Fjalla+One&display=swap');

.toolbar {
  display: flex;
  position: fixed;
  top: 0;
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

.backGround {
  background-image: url('https://cdn.discordapp.com/attachments/1034844300867031232/1035780120193024011/DD_Banner2.png ');
  background-position: center;
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
</style>
