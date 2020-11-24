<template>
  <div class="container">
    <div class="header">
      <h2 class="subtitle">Hi, I'm</h2>
      <h1 class="title">Samuel GALIERE</h1>
      <h2 id="job" class="subtitle"> and I'm a developper.</h2>
      <button onClick="javascript:window.location.href='https://pornhub.com'">Edit</button>
      <img id="background" src="../images/background.jpg"/>
    </div>
    <div>
      <DescriptionBlock 
      titre="TETSTSTE"
      contenu="etsikjfhesih fesihf leishfg leskjfeheslmkjfh elskfjh "/>
      <DescriptionBlock 
      titre="TETSTSTE"
      contenu="etsikjfhesih fesihf leishfg leskjfeheslmkjfh elskfjh "/>
    </div>
    <div>
      <ExperienceVignette 
      titre="test"
      imageURL="testg"/>
      <ExperienceDetail
      ExperienceTitre="jegzfieefojef"
      date="12/12/1222"
      description="ikerhfghemoihfeosutfpsiufjgiugfesofhesiufgsfeihe"/>
      <ExperienceVignette 
      titre="etziyu ugfi"
      imageURL="test"/>
      <ExperienceDetail
      ExperienceTitre="jegzfieefojef"
      date="12/12/1222"
      description="ikerhfghemoihfeosutfpsiufjgiugfesofhesiufgsfeihe"/>
    </div>
    <div>
      <Skill
      label="testest"
      progress="50"/>
      <Skill
      label="testest"
      progress="50"/>
      <Skill
      label="testest"
      progress="50"/>
      <Skill
      label="testest"
      progress="50"/>
      <Skill
      label="testest"
      progress="50"/>
      <Skill
      label="testest"
      progress="50"/>
      <Skill
      label="testest"
      progress="50"/>
    </div>
    <div>
      <FormulaireContact/>
    </div>
    <div>
      <RSContact
      icon="www.faceuibefoê.com"
      accountLink="https://www.google.fr/"
      accountName="Samuel GALIERE"/>
      <RSContact
      icon="www.faceuibefoê.com"
      accountLink="https://www.google.fr/"
      accountName="Samuel GALIERE"/>
      <RSContact
      icon="www.faceuibefoê.com"
      accountLink="https://www.google.fr/"
      accountName="Samuel GALIERE"/>



    </div>
  </div>
</template>

<script>
import DescriptionBlock from '../components/DescriptionBlock.vue'
import ExperienceDetail from '../components/ExperienceDetail.vue'
import ExperienceVignette from '../components/ExperienceVignette.vue'
import FormulaireContact from '../components/FormulaireContact.vue'
import RSContact from '../components/RSContact.vue'
import Skill from '../components/Skill.vue'

export default {
  components: { DescriptionBlock, ExperienceDetail, ExperienceVignette, Skill, FormulaireContact, RSContact },

}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 350;
  font-size: 5vw;
  color: #88bedd;
  letter-spacing: 1px;
  position: absolute;
  left: 7%;
  top: 25.5%; 
  
}

.subtitle {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  position: absolute;
  left: 7%;
  top: 20%; 
  font-size: 3vw;
  color: #a1a7adcc;
  font-weight: 100;
  letter-spacing: 1px;
}

#job {
  left: 15%;
  top: 39%; 
}

#background { 
  margin-left: 50%;
  height: auto; 
  margin-top: 0.2%;
}

.header {
  background-color: rgba(182, 182, 182, 0.342);
}

</style>