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

  <CRow :xs="{ cols: 1, gutter: 4 }" :md="{ cols: 3 }">
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="AnatoliSmorin" />
        <CCardBody>
          <CCardTitle>Anatoli Smorin</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="BobsonDugnutt" />
        <CCardBody>
          <CCardTitle>Bobson Dugnutt</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="DarrylArchideld" />
        <CCardBody>
          <CCardTitle>Darryl Archideld</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="DeanWesrey" />
        <CCardBody>
          <CCardTitle>Dean Wesrey</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="DwigtRortugal" />
        <CCardBody>
          <CCardTitle>Dwigt Rortugal</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="GlenallenMixon" />
        <CCardBody>
          <CCardTitle>Glenallen Mixon</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="JeromyGride" />
        <CCardBody>
          <CCardTitle>Jeromy Gride</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="KarlDandleton" />
        <CCardBody>
          <CCardTitle>Karl Dandleton</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="KevinNogilny" />
        <CCardBody>
          <CCardTitle>Kevin Nogilny</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="MarioMcRlwain" />
        <CCardBody>
          <CCardTitle>Mario McRlwain</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="MikeSernandez" />
        <CCardBody>
          <CCardTitle>Mike Sernandez</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="MikeTruk" />
        <CCardBody>
          <CCardTitle>Mike Truk</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="OnsonSweemey" />
        <CCardBody>
          <CCardTitle>Onson Sweemey</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="RaulChamgerlain" />
        <CCardBody>
          <CCardTitle>Raul Chamgerlain</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="ReyMcSriff" />
        <CCardBody>
          <CCardTitle>Rey McSriff</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="ScottDourque" />
        <CCardBody>
          <CCardTitle>Scott Dourque</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="ShownFurcotte" />
        <CCardBody>
          <CCardTitle>Shown Furcotte</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="SleveMcDichael" />
        <CCardBody>
          <CCardTitle>Sleve McDichael</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="TimSandaele" />
        <CCardBody>
          <CCardTitle>Tim Sandaele</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="ToddBonzalez" />
        <CCardBody>
          <CCardTitle>Todd Bonzalez</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="TonySmehrik" />
        <CCardBody>
          <CCardTitle>Tony Smehrik</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
    <CCol xs>
      <CCard>
        <CCardImage orientation="top" :src="WillieDustice" />
        <CCardBody>
          <CCardTitle>Willie Dustice</CCardTitle>
          <CCardText>
          </CCardText>
        </CCardBody>
        <CCardFooter>
          <small class="text-medium-emphasis"></small>
        </CCardFooter>
      </CCard>
    </CCol>
  </CRow>

</template>
