<script setup lang="ts">
</script>

<template>
  <section>
    <div>
      <h2>Wat we doen</h2>
    </div>
    <div class="flex-contain">
      <div
          data-aos="zoom-in-left"
          data-aos-duration="1500"
          class="container-1">
        <p class="title-uppercase">Webdesign</p>
        <hr>
        <p>
          Ons getalenteerde team van ontwerpers zet zich in voor het maken van verbluffende en intuïtieve webdesigns die
          de gebruikerservaring optimaliseren en de conversies verhogen.
        </p>
        <hr class="separator">
      </div>
      <div
          data-aos="zoom-in-left"
          data-aos-duration="1500"
          class="container-2">
        <p class="title-uppercase">Development</p>
        <hr>
        <p>
          Met onze expertise in development streven we ernaar om niet alleen functionele, maar ook geavanceerde en
          schaalbare websites en webapplicaties te bouwen die aan de behoeften van onze klanten voldoen.
        </p>
        <hr class="separator">
      </div>
      <div
          data-aos="zoom-in-left"
          data-aos-duration="1500"
          class="container-3">
        <p class="title-uppercase">Branding</p>
        <hr>
        <p>
          Wij geloven dat een sterk merk essentieel is voor succes. Daarom helpen we onze klanten bij het ontwikkelen
          van een consistente en onderscheidende merkidentiteit die resoneren met hun doelgroep.
        </p>
      </div>
    </div>
  </section>
</template>

<style scoped>

section {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: var(--secundair-color-l-purple);
  margin: 2rem;
  border-radius: 15px;
  overflow: clip;
}



h2 {
  color: var(--second-background);
  text-transform: uppercase;
  text-align: left;
  font-size: 12rem;
  line-height: 12rem;
  margin: 0 5rem;
}

.flex-contain {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 5rem;
  padding-top: 6rem;
}

.title-uppercase {
  font-size: 3rem;
  margin-bottom: 1rem;
  color: var(--background-dark-purple);
}

hr {
  border: solid 3px;
  border-radius: 20px;
  max-width: 7rem;
  color: var(--second-background);
  margin-bottom: 2rem;
}

p {
  color: var(--background-dark-purple);
  font-size: 1.2rem;
  margin-bottom: 5rem;
  padding-right: 10rem;
}

.separator {
  min-width: 100%;
  border: solid 3px;
  border-radius: 20px;
  color: var(--second-background);
  margin-left: auto;
  opacity: 0.3;
}

/* Media queries voor verschillende schermformaten */

/* LAPTOP */
@media screen and (max-width: 80rem) {
  h2 {
    font-size: 6rem;
  }
}

/* TABLET */
@media screen and (max-width: 60rem) {
  section {
    margin: 2rem 2rem 0 2rem;
    flex-direction: column;
  }


  h2 {
    font-size: 4.5rem;
    line-height: 5rem;
    text-align: center;
    margin-top: 5rem;
  }

  p {
    font-size: 1rem;
  }

  .flex-contain {
    margin-left: 3rem;
  }

  .separator {
   display: none;
  }
}

/* MOBILE L */
@media screen and (max-width: 30rem) {
  section {
    margin: 1rem 1rem 0 1rem;
  }

  h2 {
    font-size: 3rem;
    line-height: 3.5rem;
    text-align: center;
    width: 90vw;
    margin-bottom: 3rem;
  }

  .flex-contain {
    margin-left: 10rem;
    padding-top: 2rem;
    gap: 2rem
  }
}

</style>
