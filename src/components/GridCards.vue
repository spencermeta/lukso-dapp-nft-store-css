<script>
import VueImg from '@/assets/images/vue.jpg'

import AnatoliSmorin from '@/assets/images/Anatoli Smorin.jpg';
import BobsonDugnutt from '@/assets/images/Bobson Dugnutt.jpg';
import DarrylArchideld from '@/assets/images/Darryl Archideld.jpg';
import DeanWesrey from '@/assets/images/Dean Wesrey.jpg';
import DwigtRortugal from '@/assets/images/Dwigt Rortugal.jpg';
import GlenallenMixon from '@/assets/images/Glenallen Mixon.jpg';
import JeromyGride from '@/assets/images/Jeromy Gride.jpg';
import KarlDandleton from '@/assets/images/Karl Dandleton.jpg';
import KevinNogilny from '@/assets/images/Kevin Nogilny.jpg';
import MarioMcRlwain from '@/assets/images/Mario McRlwain.jpg';
import MikeSernandez from '@/assets/images/Mike Sernandez.jpg';
import MikeTruk from '@/assets/images/Mike Truk.jpg';
import OnsonSweemey from '@/assets/images/Onson Sweemey.jpg';
import RaulChamgerlain from '@/assets/images/Raul Chamgerlain.jpg';
import ReyMcSriff from '@/assets/images/Rey McSriff.jpg';
import ScottDourque from '@/assets/images/Scott Dourque.jpg';
import ShownFurcotte from '@/assets/images/Shown Furcotte.jpg';
import SleveMcDichael from '@/assets/images/Sleve McDichael.jpg';
import TimSandaele from '@/assets/images/Tim Sandaele.jpg';
import ToddBonzalez from '@/assets/images/Todd Bonzalez.jpg';
import TonySmehrik from '@/assets/images/Tony Smehrik.jpg';
import WillieDustice from '@/assets/images/Willie Dustice.jpg';

export default {
  name: 'GridCards',
  setup() {
    return {
      VueImg,
      AnatoliSmorin,
      BobsonDugnutt,
      DarrylArchideld,
      DeanWesrey,
      DwigtRortugal,
      GlenallenMixon,
      JeromyGride,
      KarlDandleton,
      KevinNogilny,
      MarioMcRlwain,
      MikeSernandez,
      MikeTruk,
      OnsonSweemey,
      RaulChamgerlain,
      ReyMcSriff,
      ScottDourque,
      ShownFurcotte,
      SleveMcDichael,
      TimSandaele,
      ToddBonzalez,
      TonySmehrik,
      WillieDustice,
    }
  },
}
</script>

<template>
  <a-row>
    <a-col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="AnatoliSmorin" />
        </template>
        <a-card-meta title="Anatoli Smorin">
        </a-card-meta>
      </a-card>
    </a-col>
    <a-col :xs="{ span: 11, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="BobsonDugnutt" />
        </template>
        <a-card-meta title="Bobson Dugnutt">
        </a-card-meta>
      </a-card>
    </a-col>
    <a-col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="DarrylArchideld" />
        </template>
        <a-card-meta title="Darryl Archideld">
        </a-card-meta>
      </a-card>
    </a-col>
  </a-row>

  <a-row>
    <a-col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="DeanWesrey" />
        </template>
        <a-card-meta title="Dean Wesrey">
        </a-card-meta>
      </a-card>
    </a-col>
    <a-col :xs="{ span: 11, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="DwigtRortugal" />
        </template>
        <a-card-meta title="Dwigt Rortugal">
        </a-card-meta>
      </a-card>
    </a-col>
    <a-col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="GlenallenMixon" />
        </template>
        <a-card-meta title="Glenallen Mixon">
        </a-card-meta>
      </a-card>
    </a-col>
  </a-row>

  <a-row>
    <a-col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="JeromyGride" />
        </template>
        <a-card-meta title="Jeromy Gride">
        </a-card-meta>
      </a-card>
    </a-col>
    <a-col :xs="{ span: 11, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="KarlDandleton" />
        </template>
        <a-card-meta title="Karl Dandleton">
        </a-card-meta>
      </a-card>
    </a-col>
    <a-col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="KevinNogilny" />
        </template>
        <a-card-meta title="Kevin Nogilny">
        </a-card-meta>
      </a-card>
    </a-col>
  </a-row>

  <a-row>
    <a-col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="MarioMcRlwain" />
        </template>
        <a-card-meta title="Mario McRlwain">
        </a-card-meta>
      </a-card>
    </a-col>
    <a-col :xs="{ span: 11, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="MikeSernandez" />
        </template>
        <a-card-meta title="Mike Sernandez">
        </a-card-meta>
      </a-card>
    </a-col>
    <a-col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="MikeTruk" />
        </template>
        <a-card-meta title="Mike Truk">
        </a-card-meta>
      </a-card>
    </a-col>
  </a-row>

  <a-row>
    <a-col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="OnsonSweemey" />
        </template>
        <a-card-meta title="Onson Sweemey">
        </a-card-meta>
      </a-card>
    </a-col>
    <a-col :xs="{ span: 11, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="RaulChamgerlain" />
        </template>
        <a-card-meta title="Raul Chamgerlain">
        </a-card-meta>
      </a-card>
    </a-col>
    <a-col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="ReyMcSriff" />
        </template>
        <a-card-meta title="Rey McSriff">
        </a-card-meta>
      </a-card>
    </a-col>
  </a-row>

  <a-row>
    <a-col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="ScottDourque" />
        </template>
        <a-card-meta title="Scott Dourque">
        </a-card-meta>
      </a-card>
    </a-col>
    <a-col :xs="{ span: 11, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="ShownFurcotte" />
        </template>
        <a-card-meta title="Shown Furcotte">
        </a-card-meta>
      </a-card>
    </a-col>
    <a-col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="SleveMcDichael" />
        </template>
        <a-card-meta title="Sleve McDichael">
        </a-card-meta>
      </a-card>
    </a-col>
  </a-row>

  <a-row>
    <a-col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="TimSandaele" />
        </template>
        <a-card-meta title="Tim Sandaele">
        </a-card-meta>
      </a-card>
    </a-col>
    <a-col :xs="{ span: 11, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="ToddBonzalez" />
        </template>
        <a-card-meta title="Todd Bonzalez">
        </a-card-meta>
      </a-card>
    </a-col>
    <a-col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="TonySmehrik" />
        </template>
        <a-card-meta title="Tony Smehrik">
        </a-card-meta>
      </a-card>
    </a-col>
  </a-row>

  <a-row>
    <a-col :xs="{ span: 5, offset: 1 }" :lg="{ span: 6, offset: 2 }">
      <a-card hoverable style="width: 240px">
        <template #cover>
          <img alt="example" :src="WillieDustice" />
        </template>
        <a-card-meta title="Willie Dustice">
        </a-card-meta>
      </a-card>
    </a-col>

  </a-row>
</template>
