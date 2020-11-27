<template>
  <div class="containerD">
    <meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no">
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <meta name="HandheldFriendly" content="true">
    <div class="blockSovietique">
      <h2 class="subtitle">Bonjour, je me présente,</h2>
      <h1 class="title">Samuel GALIERE</h1>
      <h2 id="job" class="subtitle"> je suis développeur.</h2>
      <img id="backgroundImage" src="../images/background.jpg"/>
      <Contact />
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
    <h3 class="baliseExperience">Expérience Profesionnelle</h3>
    <Experience
    nomEntreprise="Bhales"
    logoEntreprise="../images/firefox-nouveau-logo-770.jpg"
    ExperienceTitre="Stage de Troisième"
    date="12/12/1222"
    description="ikerhfghemoihfeosutfpsiuf yuioeg oufyige fuoig oisufgeosiuf gouiyesyg fouisgefuipges fouigs ouyfeg sougf ouiesg oifpugs oufg esouifg souif geoyug jgiugfesofhesiufgsfeihe"/>
    <Experience
    nomEntreprise="Bhales"
    logoEntreprise="../images/firefox-nouveau-logo-770.jpg"
    ExperienceTitre="Stage de Troisième"
    date="12/12/1222"
    description="ikerhfghemoihfeosutfpsiuf yuioeg oufyige fuoig oisufgeosiuf gouiyesyg fouisgefuipges fouigs ouyfeg sougf ouiesg oifpugs oufg esouifg souif geoyug jgiugfesofhesiufgsfeihe"/>

    <h3 class="baliseExperience">Diplômes</h3>
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
    <h3 class="baliseExperience" id="skills">Compétences Techniques</h3>
    <div class="blockColomn">
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

    <div class="blockColomn">
      <Skill
      label="Python"
      progress="width: 50%"/>
      <Skill
      label="HTML5"
      progress="50"/>
      <Skill
      label="testest"
      progress="50"/>
    </div>
  </div>
    <div class="blockSovietique">
      <br><br><br><br><br>
      <div class="row">
        <div id="titleFooter" class="column footerColomn">
            <h3>Je suis disponible !</h3>
        </div>
        <div class="column footerColomn">
          <div class="column footerColomn">
            <h4>Social</h4>
            <p><a target="_blanc" href="https://www.linkedin.com/in/samuel-galiere/">LinkedIn</a></p>
            <p><a target="_blank" href="https://github.com/Y0hark">GitHub</a></p>
          </div>
          <div class="column footerColomn">
              <h4>Contacts</h4>
              <p><a href="mailto:samuelgaliere.pro@gmail.com">Mon Mail</a></p>
              <p><a href="tel:+33782567456">+33782567456</a></p>
          </div>
        </div>
      </div>
      <br><br><br><br><br>
    </div>
  </div>
</template>

<script>
import Contact from '../components/Contact.vue'
import DescriptionBlock from '../components/DescriptionBlock.vue'
import Experience from '../components/Experience.vue'
import Skill from '../components/Skill.vue'

export default {
  components: { DescriptionBlock, Experience, Skill, Contact },
  head: {
    link: [
      {
        rel: 'stylesheet',
        href: 'https://bootswatch.com/4/darkly/bootstrap.css'
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

.baliseExperience{
  position: relative;
  text-align: left;
  left: 20.4%;
}

.blockSovietique {
  background-color: rgba(255, 255, 255, 0.301);
}

#skills{
  padding: 1%;
}

.footerColomn{
  display: inline-block;
  text-align: left;
  left: 20.5%;
  position: relative;
  padding: 0.5%;
  width: 30%;
  vertical-align: top;
}



</style>