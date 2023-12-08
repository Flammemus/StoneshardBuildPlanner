<script>
  import StrengthStat from './lib/StrengthStat.svelte';
</script>

<main>
  <div class="main">
    <div class="characterMain">
      <span class="characterHeader">CHARACTER</span>
      <div class="characterContainer">
        <div class="characterBackground" id="characterBackgroundTop"></div>
        <div class="characterStatsContainer">
          <div class="characterLevelContainer">
            <div class="characterNameContainer">

            </div>
            <div class="characterLevelContainer2">

              <StrengthStat/>

            </div>
          </div>
          <div class="characterAttributesContainer">

          </div>
        </div>
        <div class="characterBackground" id="characterBackgroundBottom"></div>
      </div>
    </div>

    <div class="skillsMain">

    </div>
  </div>
</main>