<template>
  <div class="container">
    <div id="header">
      <h1 class="title">Samuel GALIERE</h1>
      <img id="background" src="../images/background.jpg" />
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
  </div>
</template>

<script>
import DescriptionBlock from '../components/DescriptionBlock.vue'
import ExperienceDetail from '../components/ExperienceDetail.vue'
import ExperienceVignette from '../components/ExperienceVignette.vue'
import FormulaireContact from '../components/FormulaireContact.vue'
import Skill from '../components/Skill.vue'

export default {
  components: { DescriptionBlock, ExperienceDetail, ExperienceVignette, Skill, FormulaireContact },

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
  font-weight: 300;
  font-size: 100px;
  color: #accaeb;
  letter-spacing: 1px;
  position: absolute; 
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

#header {
  position: relative;  
  text-align: center;
}

#background {
  width: 100%;

}

</style>