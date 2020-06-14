<template>
  <div class="container">
    <div class="card">
      <h1 class="title">
        🤍Jake & Maili Have A Wedding🤍
      </h1>
      <h2 class="subtitle">
        📅: 07.14.2021, 🗺️:
        <a href="http://bit.ly/2tw5xa9" class="links">
          River Garden Winery
        </a>
      </h2>
      <p class="note">
        COVID-19 Affected the Date.
        Please see
        <router-link to="/details" target="self" class="links">
          Details
        </router-link>
        for more info
      </p>
      <p class="content">
        We've tried to provide accurate information for you here. But, wedding
        planning is no easy task. If you have any specific questions, feel free
        to reach out and call either of us directly.
      </p>
    </div>
  </div>
</template>

<style>
p.note {

  background-color: #f0f7fb;
  background-image: url("/Warning-Message-256.png");
  background-size: 7vh;
  background-position: .25vw .2vh;
  background-repeat: no-repeat;
  border-left: solid 4px #3498db;
  line-height: 18px;
  overflow: hidden;
  padding: 15px 60px;

}
</style>

