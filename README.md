<svg viewBox="0 0 200 100" width="400" height="200" xmlns="http://www.w3.org/2000/svg">
  <style>
    .block {
      fill: #ebedf0;
      stroke: #ddd;
      stroke-width: 1px;
    }
    .snake {
      fill: #40c463;
      animation: move 4s infinite;
    }
    @keyframes move {
      0% { transform: translate(0, 0); }
      25% { transform: translate(50px, 0); }
      50% { transform: translate(50px, 50px); }
      75% { transform: translate(0, 50px); }
      100% { transform: translate(0, 0); }
    }
  </style>
  <!-- Background grid -->
  <rect class="block" x="0" y="0" width="20" height="20" />
  <rect class="block" x="20" y="0" width="20" height="20" />
  <rect class="block" x="40" y="0" width="20" height="20" />
  <rect class="block" x="60" y="0" width="20" height="20" />
  <rect class="block" x="80" y="0" width="20" height="20" />

  <!-- Serpent -->
  <rect class="snake" x="0" y="0" width="20" height="20" />
</svg>
