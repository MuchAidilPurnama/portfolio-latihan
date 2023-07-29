<template>
  <div class="projcard-container">
		
    <div class="projcard projcard-blue">
      <div class="projcard-innerbox">
        <img class="projcard-img" src="https://picsum.photos/800/600?image=1041" />
        <div class="projcard-textbox">
          <div class="projcard-title">Sekolah Saya</div>
          <div class="projcard-subtitle">Ini Adalah Detailnya dari Sekolah Saya</div>
          <div class="projcard-bar"></div>
          <div class="projcard-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</div>
          <div class="projcard-tagbox">
            <span class="projcard-tag">Bandung</span>
            <span class="projcard-tag">Cibaduyut</span>
          </div>
        </div>
      </div>
    </div>
    
    <div class="projcard projcard-red">
      <div class="projcard-innerbox">
        <img class="projcard-img" src="https://picsum.photos/800/600?image=1080" />
        <div class="projcard-textbox">
          <div class="projcard-title">Hoby</div>
          <div class="projcard-subtitle">Saya tidak tau apa yang saya sukai tapi kayaknya ini</div>
          <div class="projcard-bar"></div>
          <div class="projcard-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</div>
          <div class="projcard-tagbox">
            <span class="projcard-tag">GAME</span>
            <span class="projcard-tag">MLBB</span>
            <span class="projcard-tag">Juara Dunia</span>
          </div>
        </div>
      </div>
    </div>
    
    <div class="projcard projcard-green">
      <div class="projcard-innerbox">
        <img class="projcard-img" src="https://picsum.photos/800/600?image=1039" />
        <div class="projcard-textbox">
          <div class="projcard-title"></div>
          <div class="projcard-subtitle">Pengalaman</div>
          <div class="projcard-bar"></div>
          <div class="projcard-description">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.</div>
          <div class="projcard-tagbox">
            <span class="projcard-tag">NodeJs</span>
            <span class="projcard-tag">VueJs</span>
          </div>
        </div>
      </div>
    </div>
    
    <div class="projcard projcard-customcolor" style="--projcard-color: #F5AF41;">
      <div class="projcard-innerbox">
        <img class="projcard-img" src="https://picsum.photos/800/600?image=943" />
        <div class="projcard-textbox">
          <div class="projcard-title">Project</div>
          <div class="projcard-subtitle">Ketika kelas 12 ini akan jadi project terakhir saya</div>
          <div class="projcard-bar"></div>
          <div class="projcard-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</div>
          <div class="projcard-tagbox">
            <span class="projcard-tag">VueJs</span>
            <span class="projcard-tag">Semangat</span>
            <span class="projcard-tag">Smk Assalaam</span>
          </div>
        </div>
      </div>
    </div>
    
  </div>
</template>
<script>
document.querySelectorAll(".projcard-description").forEach(function(box) {
	$clamp(box, {clamp: 6});
});
</script>