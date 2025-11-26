<template>
  <main>
    <section id="home" class="home-section">
      <h1 class="home-title">Bienvenue sur mon portfolio</h1>
      <p class="home-text">Découvrez mes projets, compétences et parcours.</p>
    </section>
    <section id="apropos">
      <h2>A propos de moi</h2>
      <p>
        Je m'appelle NZODOM Kylian,étudiant en informatique actuellement a la
        recherche d'une alternance.
      </p>
    </section>
    <section id="soft-skills">
      <h2>Soft skills</h2>
      <ul>
        <li>Extravertie</li>
        <li>Dynamique</li>
        <li>Rigoureux</li>
        <li>jovial</li>
      </ul>
    </section>
    <section id="realisations">
      <h2>Réalisations</h2>
      <p>
        Ce portfolio est ma première réalisation : il a été conçu entièrement
        par moi-même en HTML et CSS.<br />
        Il me permet d’apprendre le développement web et de montrer mes progrès
      </p>
    </section>
    <section id="technologie">
      <h2>Technologie</h2>
      <div class="tech-container">
        <div class="tech-item">
          <p>HTML</p>
        </div>
        <div class="tech-item">
          <p>CSS</p>
        </div>
        <div class="tech-item">
          <p>Photoshop</p>
        </div>
      </div>
    </section>
    <div>
      <section id="parcours">
        <h2>Mon Parcours</h2>
        <h3>Sup'Formation - (en cours)</h3>
        <p>BTS Services Informatiques aux Organisations</p>
        <h3>Lycée Paul Valéry - 2022/23</h3>
        <p>Baccalauréat STI2D</p>
        <h3></h3>
      </section>

      <section id="contacts">
        <h2>Contacts</h2>
      </section>

      <section id="liensutiles">
        <h2>Liens utiles</h2>

        <a href="https://github.com">GitHub</a>
      </section>
    </div>
  </main>
  <a href="#top" class="back-to-top" aria-label="Remonter en haut">↑</a>
  <!-- Code HTML du portfolio -->
</template>

<script>
export default {
  name: "Portfolio",
};
</script>

<style scoped>
/* Code CSS du portfolio */
</style>
