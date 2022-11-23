<template>
  <q-page class="flex container backGroundTeam flex-center">
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
          <q-btn target="_blank" href="https://deadsouls-staking.web.app/" style="margin-right: -1.5em "
            class="textFjala qbtnn text-subtitle text-bold" flat color="black" text-color="white" label="STAKING">
          </q-btn>
          <q-btn target="_blank" href="https://raffle-dsd.vercel.app/" class="textFjala qbtnn text-subtitle text-bold"
            flat color="black" text-color="white" label="RAFFLES">
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
          <q-btn target="_blank" href="https://deadsouls-staking.web.app/" style="margin-right: -1.5em "
            class="textFjala qbtnn text-subtitle text-bold" flat color="black" text-color="white" label="STAKING">
          </q-btn>
          <q-btn target="_blank" href="https://raffle-dsd.vercel.app/" class="textFjala qbtnn text-subtitle text-bold"
            flat color="black" text-color="white" label="RAFFLES">
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
              <q-item-section>
                <span class="textFjala">RAFFLE</span>
              </q-item-section>
            </q-item>

            <q-item target="_blank" href="https://deadsouls-staking.web.app/" clickable v-close-popup
              @click="onItemClick">
              <q-item-section>
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

    <!-- TEAM CARD -->
    <!-- XL SIZE -->
    <div style="margin-top: 11em" class="q-gutter-md gt-lg flex flex-center  ">
      <q-card style="opacity: 0.95; border-radius: 20px;" class="team-card-xl bg-transparent" flat bordered>
        <q-card-section class="bgblue" horizontal>
          <q-item-section style="margin-top: -8em" class="absolute-top flex flex-end shadow-12" avatar>
            <q-avatar size="220px">
              <img class="fixed"
                src="https://cdn.discordapp.com/attachments/1034844300867031232/1034931930963120158/51.jpeg">
            </q-avatar>
          </q-item-section>
          <q-card-section class="text-white textKdam ">
            <h5 style="margin-left: 3em; text-decoration: underline;" class="text-center text-white q-py-lg q-ma-md">
              Punk</h5>
            <h6 class="q-ma-none">Founder</h6>
            <hr style="opacity: 0.3;">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Distinctio nobis in quisquam laborum eos. Culpa
            aut numquam minus pariatur architecto laudantium inventore illum mollitia ducimus tempora, aperiam, illo
            iste odio?

          </q-card-section>
        </q-card-section>

        <q-card-section class="bgblue" horizontal>
          <q-card-actions horizontal class="justify-around">
            <q-btn flat round target="_blank" href="https://twitter.com/Punksol" class="inset-shadow" color="white"
              icon="fa-brands fa-twitter" />

          </q-card-actions>
        </q-card-section>

      </q-card>

      <q-card style="opacity: 0.95; border-radius: 20px;" class="team-card-xl bg-transparent" flat bordered>
        <q-card-section class="bgblue" horizontal>
          <q-item-section style="margin-top: -8em" class="absolute-top flex flex-end shadow-12" avatar>
            <q-avatar size="220px">
              <img src="https://cdn.discordapp.com/attachments/1034844300867031232/1034931930656952452/41.jpeg">
            </q-avatar>
          </q-item-section>
          <q-card-section class="text-white textKdam ">
            <h5 style="margin-left: 3em; text-decoration: underline;" class="text-center q-py-lg q-ma-md">Amn3sia</h5>
            <h6 class="q-ma-none">Business Dev</h6>
            <hr style="opacity: 0.3;">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aperiam eos eligendi optio dolorem pariatur
            laborum itaque debitis nihil error? Molestias architecto voluptatem iusto ipsum beatae? Hic aspernatur quas
            eveniet voluptas?

            <q-separate />

          </q-card-section>
        </q-card-section>

        <q-card-section class="bgblue" horizontal>
          <q-card-actions horizontal class="justify-around flex items-end">
            <q-btn flat round target="_blank" href="https://twitter.com/Amn3sia" class="inset-shadow" color="white"
              icon="fa-brands fa-twitter" />

          </q-card-actions>
        </q-card-section>

      </q-card>

      <q-card style="opacity: 0.95; border-radius: 20px;" class="team-card-xl bg-transparent" flat bordered>
        <q-card-section class="bgblue" horizontal>
          <q-item-section style="margin-top: -8em" class="absolute-top flex flex-end shadow-12" avatar>
            <q-avatar size="220px">
              <img src="https://cdn.discordapp.com/attachments/1034844300867031232/1034931930384318484/98.jpeg">
            </q-avatar>
          </q-item-section>
          <q-card-section class="text-white textKdam ">
            <h5 style="margin-left: 3em; text-decoration: underline;" class="text-center q-py-lg q-ma-md">Artist</h5>
            <h6 class="q-ma-none">Artist</h6>
            <hr style="opacity: 0.2;">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quam iusto, eius error ullam exercitationem autem
            odit illum perspiciatis accusamus? Voluptate provident quis tempora laudantium beatae ad esse eaque nisi
            totam.
          </q-card-section>



        </q-card-section>

        <q-card-section class="bgblue" horizontal>
          <q-card-actions horizontal class="justify-around">
            <q-btn flat round target="_blank" href="https://twitter.com/ArtistNFTs" class="inset-shadow" color="white"
              icon="fa-brands fa-twitter" />

          </q-card-actions>
        </q-card-section>

      </q-card>

    </div>

    <!-- LG SIZE -->
    <div style="margin-top: 11em" class="q-gutter-md lt-xl gt-md flex flex-center  ">
      <q-card style="opacity: 0.95; border-radius: 20px;" class="team-card-lg bg-transparent" flat bordered>
        <q-card-section class="bgblue" horizontal>
          <q-item-section style="margin-top: -8.5em" class="absolute-top flex flex-center shadow-12" avatar>
            <q-avatar size="180px">
              <img
                src="https://cdn.discordapp.com/attachments/1034844300867031232/1034931930963120158/51.jpeg">
            </q-avatar>
          </q-item-section>
          <q-card-section class="text-white textKdam ">
            <h5 style="margin-top: 2em; margin-bottom: -0.5em; text-decoration: underline;"
              class="text-center text-white q-py-lg q-ma-md">Punk</h5>
            <h6 class="q-ma-none">Founder</h6>
            <hr style="opacity: 0.3;">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Distinctio nobis in quisquam laborum eos. Culpa
            aut numquam minus pariatur architecto laudantium inventore illum mollitia ducimus tempora, aperiam, illo
            iste odio?
          </q-card-section>
        </q-card-section>

        <q-card-section class="bgblue" horizontal>
          <q-card-actions horizontal class="justify-around">
            <q-btn flat round target="_blank" href="https://twitter.com/Punksol" class="inset-shadow" color="white"
              icon="fa-brands fa-twitter" />

          </q-card-actions>
        </q-card-section>

      </q-card>

      <q-card style="opacity: 0.95; border-radius: 20px;" class="team-card-lg bg-transparent" flat bordered>
        <q-card-section class="bgblue" horizontal>
          <q-item-section style="margin-top: -8.5em" class="absolute-top flex flex-center shadow-12" avatar>
            <q-avatar size="180px">
              <img src="https://cdn.discordapp.com/attachments/1034844300867031232/1034931930656952452/41.jpeg">
            </q-avatar>
          </q-item-section>
          <q-card-section class="text-white textKdam ">
            <h5 style="margin-top: 2em; margin-bottom: -0.5em; text-decoration: underline;"
              class="text-center text-white q-py-lg q-ma-md">Amn3sia</h5>
            <h6 class="q-ma-none">Developer</h6>
            <hr style="opacity: 0.3;">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Distinctio nobis in quisquam laborum eos. Culpa
            aut numquam minus pariatur architecto laudantium inventore illum mollitia ducimus tempora, aperiam, illo
            iste odio?

          </q-card-section>
        </q-card-section>

        <q-card-section class="bgblue" horizontal>
          <q-card-actions horizontal class="justify-around">
            <q-btn flat round target="_blank" href="https://twitter.com/Amn3sia" class="inset-shadow" color="white"
              icon="fa-brands fa-twitter" />

          </q-card-actions>
        </q-card-section>

      </q-card>

      <q-card style="opacity: 0.95; border-radius: 20px;" class="team-card-lg bg-transparent" flat bordered>
        <q-card-section class="bgblue" horizontal>
          <q-item-section style="margin-top: -8.5em" class="absolute-top flex flex-center shadow-12" avatar>
            <q-avatar size="180px">
              <img src="https://cdn.discordapp.com/attachments/1034844300867031232/1034931930384318484/98.jpeg">
            </q-avatar>
          </q-item-section>
          <q-card-section class="text-white textKdam ">
            <h5 style="margin-top: 2em; margin-bottom: -0.6em; text-decoration: underline;"
              class="text-center text-white q-py-lg q-ma-md">Artist</h5>
            <h6 class="q-ma-none">Artist</h6>
            <hr style="opacity: 0.3;">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Distinctio nobis in quisquam laborum eos. Culpa
            aut numquam minus pariatur architecto laudantium inventore illum mollitia ducimus tempora, aperiam, illo
            iste odio?
          </q-card-section>
        </q-card-section>

        <q-card-section class="bgblue" horizontal>
          <q-card-actions horizontal class="justify-around">
            <q-btn flat round target="_blank" href="https://twitter.com/ArtistNFTs" class="inset-shadow" color="white"
              icon="fa-brands fa-twitter" />

          </q-card-actions>
        </q-card-section>

      </q-card>

    </div>

    <!-- MD SIZE -->
    <div style="margin-top: 5em; margin-bottom: 3em;" class="q-gutter-md gt-sm lt-lg flex col flex-center  ">
      <q-card style="opacity: 0.95; border-radius: 20px;" class="team-card-md bg-transparent" flat bordered>
        <q-card-section class="bgblue" horizontal>
          <q-item-section style="margin-top: -7em" class="absolute-top flex flex-center shadow-12" avatar>
            <q-avatar size="150px">
              <img
                src="https://cdn.discordapp.com/attachments/1034844300867031232/1034931930963120158/51.jpeg">
            </q-avatar>
          </q-item-section>
          <q-card-section class="text-white textKdam ">
            <h5 style="margin-top: 2em; margin-bottom: -0.5em; text-decoration: underline;"
              class="text-center text-white q-py-lg q-ma-md">Punk</h5>
            <h6 class="q-ma-none">Founder</h6>
            <hr style="opacity: 0.3;">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Distinctio nobis in quisquam laborum eos. Culpa
            aut numquam minus pariatur architecto laudantium inventore illum mollitia ducimus tempora, aperiam, illo
            iste odio?

          </q-card-section>
        </q-card-section>

        <q-card-section class="bgblue" horizontal>
          <q-card-actions horizontal class="justify-around">
            <q-btn flat round target="_blank" href="https://twitter.com/Punksol" class="inset-shadow" color="white"
              icon="fa-brands fa-twitter" />

          </q-card-actions>
        </q-card-section>

      </q-card>

      <q-card style="opacity: 0.95; border-radius: 20px;" class="team-card-md bg-transparent" flat bordered>
        <q-card-section class="bgblue" horizontal>
          <q-item-section style="margin-top: -7em" class="absolute-top flex flex-center shadow-12" avatar>
            <q-avatar size="150px">
              <img src="https://cdn.discordapp.com/attachments/1034844300867031232/1034931930656952452/41.jpeg">
            </q-avatar>
          </q-item-section>
          <q-card-section class="text-white textKdam ">
            <h5 style="margin-top: 2em; margin-bottom: -0.5em; text-decoration: underline;"
              class="text-center text-white q-py-lg q-ma-md">Amn3sia</h5>
            <h6 class="q-ma-none">Developer</h6>
            <hr style="opacity: 0.3;">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Distinctio nobis in quisquam laborum eos. Culpa
            aut numquam minus pariatur architecto laudantium inventore illum mollitia ducimus tempora, aperiam, illo
            iste odio?
          </q-card-section>
        </q-card-section>

        <q-card-section class="bgblue" horizontal>
          <q-card-actions horizontal class="justify-around">
            <q-btn flat round target="_blank" href="https://twitter.com/Amn3sia" class="inset-shadow" color="white"
              icon="fa-brands fa-twitter" />

          </q-card-actions>
        </q-card-section>

      </q-card>

      <q-card style="opacity: 0.95; border-radius: 20px;" class="team-card-md bg-transparent" flat bordered>
        <q-card-section class="bgblue" horizontal>
          <q-item-section style="margin-top: -7em" class="absolute-top flex flex-center shadow-12" avatar>
            <q-avatar size="150px">
              <img src="https://cdn.discordapp.com/attachments/1034844300867031232/1034931930384318484/98.jpeg">
            </q-avatar>
          </q-item-section>
          <q-card-section class="text-white textKdam ">
            <h5 style="margin-top: 2em; margin-bottom: -0.6em; text-decoration: underline;"
              class="text-center text-white q-py-lg q-ma-md">Artist</h5>
            <h6 class="q-ma-none">Artist</h6>
            <hr style="opacity: 0.3;">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Distinctio nobis in quisquam laborum eos. Culpa
            aut numquam minus pariatur architecto laudantium inventore illum mollitia ducimus tempora, aperiam, illo
            iste odio?

          </q-card-section>
        </q-card-section>

        <q-card-section class="bgblue" horizontal>
          <q-card-actions horizontal class="justify-around">
            <q-btn flat round target="_blank" href="https://twitter.com/ArtistNFTs" class="inset-shadow" color="white"
              icon="fa-brands fa-twitter" />

          </q-card-actions>
        </q-card-section>

      </q-card>

    </div>

    <!-- SM SIZE -->
    <div style="padding-top: 10em; padding-bottom: 8em" class="flex flex-center q-ma-md  q-pa-md lt-md col q-gutter-lg">
      <q-card style="border-radius: 10px" class="my-card-mob col-1 q-mb-xl bg-transparent" flat bordered>
        <div class="flex items-center justify-center">
          <q-img style="border-radius: 10px" class="backgroundImageMob" />
        </div>

        <q-card-section style="opacity: 0.9" class="bg-black">
          <div class="text-overline textFjala text-white">founder.</div>
          <div class="text-h5 text-white textFjala q-mt-sm q-mb-xs">Punk</div>
          <div class="text-caption textFjala bg-black text-grey">
            The creator
          </div>
        </q-card-section>
      </q-card>

      <q-card style="border-radius: 10px" class="my-card-mob col-2 q-mb-xl bg-transparent" flat bordered>
        <div class="flex items-center justify-center">
          <q-img style="border-radius: 10px" class="backgroundImageMob2" />
        </div>

        <q-card-section style="opacity: 0.9" class="bg-black">
          <div class="text-overline textFjala text-white">developer</div>
          <div class="text-h5 text-white textFjala q-mt-sm q-mb-xs">Amn3sia</div>
          <div class="text-caption textFjala bg-black text-grey">
            The Builder
          </div>
        </q-card-section>
      </q-card>
      <q-card style="border-radius: 10px" class="my-card-mob col-3 q-mb-xl bg-transparent" flat bordered>
        <div class="flex items-center justify-center">
          <q-img style="border-radius: 10px" class="backgroundImageMob3" />
        </div>

        <q-card-section style="opacity: 0.9" class="bg-black">
          <div class="text-overline textFjala text-white">Artist.</div>
          <div class="text-h5 text-white textFjala q-mt-sm q-mb-xs">Artist</div>
          <div class="text-caption textFjala bg-black text-grey">
            The Artist
          </div>
        </q-card-section>
      </q-card>

    </div>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Team',
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

.bgblue {
  transition-duration: 1s;
  background-color: #04001A;
  opacity: 0.75;
}

.bgblue:hover {
  transition-duration: 1s;
  background-color: #04001A;
  opacity: 0.9;
}


.bggrey {
  background-color: #DAD4D2;
}

.bgyellow {
  background-color: #FAA305;
}

.team-card-xl {
  transition-duration: 1s;
  width: 24vw;
  height: 40vh;
}

.team-card-lg {
  transition-duration: 1s;
  width: 20vw;
  height: 35vh;
}

.team-card-md {
  transition-duration: 1s;
  width: 24vw;
  height: 35vh;
}

.my-card-mob {
  max-width: 20vw;
  max-height: 20vh;
}

.backgroundImageMob {
  width: 42vw;
  transition-duration: 1.3s;
  height: 16em;
  background-size: cover;
  background-position: center;
  background-image: url("https://cdn.discordapp.com/attachments/1034844300867031232/1034931930963120158/51.jpeg");
}

.backgroundImageMob2 {
  width: 42vw;
  transition-duration: 1.3s;
  height: 16em;
  background-size: cover;
  background-position: center;
  background-image: url("https://cdn.discordapp.com/attachments/1034844300867031232/1034931930656952452/41.jpeg");
}

.backgroundImageMob3 {
  width: 42vw;
  transition-duration: 1.3s;
  height: 16em;
  background-size: cover;
  background-position: center;
  background-image: url("https://cdn.discordapp.com/attachments/1034844300867031232/1034931930384318484/98.jpeg");
}

.text-card {
  width: 10vw;
  height: 50vh;
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

.backGroundTeam {
  background-image: url('https://cdn.discordapp.com/attachments/1034844300867031232/1035780120193024011/DD_Banner2.png');
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
