<script>
  import Counter from './lib/Counter.svelte'
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
              <!-- Attributes for character: Strength, Agility etc -->

              <div class="attributeCardContainer">
                <div class="attributeCardLeft">
                  <span class="attributeText">Strength</span>
                </div>
                <div class="attributeCardRight">
                  <span class="attributeText" id="attributeNumber">11</span>
                </div>
              </div>

              <div class="attributeCardContainer">
                <div class="attributeCardLeft">
                  <span class="attributeText">Agility</span>
                </div>
                <div class="attributeCardRight">
                  <span class="attributeText" id="attributeNumber">11</span>
                </div>
              </div>

              <div class="attributeCardContainer">
                <div class="attributeCardLeft">
                  <span class="attributeText">Perception</span>
                </div>
                <div class="attributeCardRight">
                  <span class="attributeText" id="attributeNumber">11</span>
                </div>
              </div>

              <div class="attributeCardContainer">
                <div class="attributeCardLeft">
                  <span class="attributeText">Vitality</span>
                </div>
                <div class="attributeCardRight">
                  <span class="attributeText" id="attributeNumber">10</span>
                </div>
              </div>

              <div class="attributeCardContainer">
                <div class="attributeCardLeft">
                  <span class="attributeText">Willpower</span>
                </div>
                <div class="attributeCardRight">
                  <span class="attributeText" id="attributeNumber">10</span>
                </div>
              </div>

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