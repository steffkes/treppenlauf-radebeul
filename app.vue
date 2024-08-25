<template>
  <section
    class="hero is-halfheight is-link"
    style="
      background-color: #000;
      background-image: url(/images/IMG_7000.jpg);
      background-size: cover;
      background-position: 50% 80%;
    "
  >
    <div class="hero-body" style="justify-content: center; align-items: end">
      <div style="text-align: center">
        <p class="title">Eulenlauf Radebeul</p>
        <p class="subtitle">Spitzhaustreppe</p>
      </div>
    </div>
  </section>

  <div class="container">
    <section class="hero is-small my-6">
      <div class="hero-body">
        <p class="title">Die Fakten</p>
      </div>
    </section>

    <div class="columns facts my-6">
      <div class="column">
        <p class="is-size-3"><abbr title="Samstag">Sa</abbr>, 07.09. 18 Uhr</p>
        <p>Startschuß</p>
      </div>
      <div class="column">
        <p class="is-size-3">🦉</p>
      </div>
      <div class="column">
        <p class="is-size-3"><abbr title="Samstag">Sa</abbr>, 07.09. 20 Uhr</p>
        <p>Siegerehrung</p>
      </div>
    </div>

    <div class="columns facts my-6">
      <div class="column">
        <p class="is-size-3">942</p>
        <p>Stufen</p>
      </div>
      <div class="column">
        <p class="is-size-3">935<abbr title="Meter">m</abbr></p>
        <p>Distanz</p>
      </div>
      <div class="column">
        <p class="is-size-3">182<abbr title="Höhenmeter">hm</abbr></p>
        <p>Differenz</p>
      </div>
    </div>

    <RegisterNowButton />

    <section class="hero is-small my-6">
      <div class="hero-body">
        <p class="title">Der Wettkampf</p>
      </div>
    </section>

    <p>
      Der <strong>Eulenlauf Radebeul</strong> ist ein Feuerwehr-Treppenlauf im
      2er-Trupp: Eine Runde in komplette Einsatzbekleidung und unter Atemschutz.
      Start & Ziel befinden sich <strong>oben</strong> am Bismarckturm, es geht
      also zuerst hinunter und anschließend wieder hinauf:
    </p>

    <p><img src="/images/elevation-profile.png" /></p>

    <RegisterNowButton />

    <section class="hero is-small my-6">
      <div class="hero-body">
        <p class="title">Die Treppen</p>
      </div>
    </section>

    <div class="columns">
      <div class="column">
        <img src="/images/IMG_7005.jpg" /><strong>Start</strong> &
        <strong>Ziel</strong>: Bismarckturm
      </div>
      <div class="column">
        <img src="/images/IMG_7001.jpg" /><strong>Abstieg</strong>: 397 Stufen
        abwärts
      </div>
      <div class="column">
        <img src="/images/IMG_7002.jpg" /><strong>Aufstieg</strong>: 454 Stufen
        aufwärts (nicht vollständig zu sehen)
      </div>
    </div>

    <RegisterNowButton />
  </div>

  <footer class="footer">
    <div class="content has-text-centered">
      <p>
        <strong>Eulenlauf Radebeul</strong> wird veranstaltet von
        <a href="https://feuerwehrfitness-dresden.de"
          >Feuerwehrfitness Dresden e.V.</a
        >
      </p>
    </div>
  </footer>
</template>

<style>
@import url("bulma");

abbr {
  text-decoration: none;
}

.facts .column {
  text-align: center;
}

.facts .title {
  margin-bottom: 0;
}

.hero.is-small {
  border-left: 5px solid #c0c0c0;
}
</style>

<script setup>
useSeoMeta({
  title: "Eulenlauf Radebeul",
  description: "Samstag, 07.09. @ Spitzhaustreppe Radebeul",
  ogImage: "/og.jpg",
});

useHead({
  script: [
    {
      src: "https://plausible.io/js/script.outbound-links.js",
      "data-domain": "treppenlauf-radebeul.vercel.app",
      defer: true,
    },
  ],
});

</script>
