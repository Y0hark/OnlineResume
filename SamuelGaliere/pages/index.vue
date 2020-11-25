<template>
  <div class="containerD">
    <div class="blockSovietique">
      <h2 class="subtitle">Bonjour, je me présente,</h2>
      <h1 class="title">Samuel GALIERE</h1>
      <h2 id="job" class="subtitle"> je suis développeur.</h2>
      <button type="button" class="btn btn-primary buttonContact" onClick="window.open('https://www.youtube.com/watch?v=D8KxdXEBkhw', '__blank')">Contactez-moi</button>
      <img id="backgroundImage" src="../images/background.jpg"/>
    </div>
    <div>
      
      <br>

      <DescriptionBlock class="descriptionBlock" id="profil"
      titre="Mon Profil"
      contenu=" fesihf leishfg leskjfeheslmki gfiuhg fugs iofuge zuifgeuisgfoiuesg fuiegs fiuog sipufg oeisuf goisu gfiougs fioug isugfiouseg fiugs ifujg esiugf ieusg fiuse fusip fiuesgh ofuiesg foiuegfousgf ouesgofu ysgfu gsofeuiyges ufsgefouysegfuysgepfiu siuef pesf uges foiusefg epius goifugh soiug oiugjfh elskfjh "/>
      
      <DescriptionBlock class="descriptionBlock" id="lookingFor"
      titre="Ce que je cherche"
      contenu="gzpifuzpifu g zpuig fpizug efpiuezg pifg g zpiefug zfug zpifu ghfg leskjfeheslmkjfh elskfjh "/>

      <br>

    </div>
    <div class="blockSovietique">
      <Experience
      nomEntreprise="Bhales"
      logoEntreprise="../images/firefox-nouveau-logo-770.jpg"
      ExperienceTitre="Stage de Troisième"
      date="12/12/1222"
      description="ikerhfghemoihfeosutfpsiuf yuioeg oufyige fuoig oisufgeosiuf gouiyesyg fouisgefuipges fouigs ouyfeg sougf ouiesg oifpugs oufg esouifg souif geoyug jgiugfesofhesiufgsfeihe"/>
      <Experience
      nomEntreprise="Thales"
      logoEntreprise="www.uigrezuyrfgz.fr"
      ExperienceTitre="Stage de Troisième"
      date="12/12/1222"
      description="ikerhfghemoihfeosutfpsiuf yuioeg oufyige fuoig oisufgeosiuf gouiyesyg fouisgefuipges fouigs ouyfeg sougf ouiesg oifpugs oufg esouifg souif geoyug jgiugfesofhesiufgsfeihe"/>
      <Experience
      nomEntreprise="Thales"
      logoEntreprise="www.uigrezuyrfgz.fr"
      ExperienceTitre="Stage de Troisième"
      date="12/12/1222"
      description="ikerhfghemoihfeosutfpsiuf yuioeg oufyige fuoig oisufgeosiuf gouiyesyg fouisgefuipges fouigs ouyfeg sougf ouiesg oifpugs oufg esouifg souif geoyug jgiugfesofhesiufgsfeihe"/>
      <Experience
      nomEntreprise="Thales"
      logoEntreprise="www.uigrezuyrfgz.fr"
      ExperienceTitre="Stage de Troisième"
      date="12/12/1222"
      description="ikerhfghemoihfeosutfpsiuf yuioeg oufyige fuoig oisufgeosiuf gouiyesyg fouisgefuipges fouigs ouyfeg sougf ouiesg oifpugs oufg esouifg souif geoyug jgiugfesofhesiufgsfeihe"/>
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
      <div class="blockSovietique">
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
  </div>
</template>

<script>
import DescriptionBlock from '../components/DescriptionBlock.vue'
import Experience from '../components/Experience.vue'
import FormulaireContact from '../components/FormulaireContact.vue'
import RSContact from '../components/RSContact.vue'
import Skill from '../components/Skill.vue'

export default {
  components: { DescriptionBlock, Experience, Skill, FormulaireContact, RSContact },
  head: {
    link: [
      {
        rel: 'stylesheet',
        href: 'https://bootswatch.com/4/darkly/bootstrap.min.css'
      }
    ]
  }
}
</script>

<style>
.containerD {
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
  top: 16.5%; 
  
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
  top: 11%; 
  font-size: 3vw;
  color: #a1a7adcc;
  font-weight: 100;
  letter-spacing: 1px;
}

#job {
  left: 17.5%;
  top: 27%; 
}

#backgroundImage { 
  margin-left: 50%;
  height: auto; 
  margin-top: 0.2%;
}

.blockSovietique {
  background-color: rgba(255, 255, 255, 0.301);
}

.buttonContact{
  position: absolute;
  top: 40%;
  left: 22%;
}

</style>