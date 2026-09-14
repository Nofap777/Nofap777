<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 400" width="800" height="400" preserveAspectRatio="xMidYMid meet">
  <defs>
    <!-- Background Atmospheric Night Sky Gradient -->
    <linearGradient id="city-sky-gradient" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#020003" />
      <stop offset="35%" stop-color="#090105" />
      <stop offset="70%" stop-color="#190209" />
      <stop offset="100%" stop-color="#2a0410" />
    </linearGradient>

    <!-- Crimson Smog / Fog Atmosphere Gradient -->
    <linearGradient id="crimson-smog" x1="0" y1="1" x2="0" y2="0">
      <stop offset="0%" stop-color="#ff003c" stop-opacity="0.32" />
      <stop offset="30%" stop-color="#ff2e54" stop-opacity="0.14" />
      <stop offset="70%" stop-color="#4a0515" stop-opacity="0.04" />
      <stop offset="100%" stop-color="#000000" stop-opacity="0" />
    </linearGradient>

    <!-- Drone Searchlight Beam Gradient (Cone of Light) -->
    <linearGradient id="searchlight-beam" x1="0" y1="0" x2="0.6" y2="1">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.85" />
      <stop offset="25%" stop-color="#ff2e54" stop-opacity="0.45" />
      <stop offset="70%" stop-color="#ff003c" stop-opacity="0.15" />
      <stop offset="100%" stop-color="#ff003c" stop-opacity="0" />
    </linearGradient>

    <!-- Drone 2 Scanner Beam Gradient -->
    <linearGradient id="scanner-beam-2" x1="0.5" y1="0" x2="0.5" y2="1">
      <stop offset="0%" stop-color="#ff4d6d" stop-opacity="0.75" />
      <stop offset="40%" stop-color="#ff003c" stop-opacity="0.25" />
      <stop offset="100%" stop-color="#ff003c" stop-opacity="0" />
    </linearGradient>

    <!-- Highway Traffic Light Streaks -->
    <linearGradient id="traffic-streak-red" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#ff003c" stop-opacity="0" />
      <stop offset="20%" stop-color="#ff003c" stop-opacity="1" />
      <stop offset="60%" stop-color="#ff4d6d" stop-opacity="1" />
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0.9" />
    </linearGradient>
    <linearGradient id="traffic-streak-white" x1="1" y1="0" x2="0" y2="0">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0" />
      <stop offset="30%" stop-color="#ffccd5" stop-opacity="0.8" />
      <stop offset="70%" stop-color="#ff003c" stop-opacity="0.9" />
      <stop offset="100%" stop-color="#ffffff" stop-opacity="1" />
    </linearGradient>

    <!-- HUD Shaded Glass Backing -->
    <linearGradient id="hud-glass-grad" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#0a0104" stop-opacity="0.88" />
      <stop offset="50%" stop-color="#120208" stop-opacity="0.78" />
      <stop offset="100%" stop-color="#18030b" stop-opacity="0.92" />
    </linearGradient>

    <!-- Center HUD Hologram Glow -->
    <radialGradient id="holo-glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ff003c" stop-opacity="0.4" />
      <stop offset="60%" stop-color="#ff2e54" stop-opacity="0.12" />
      <stop offset="100%" stop-color="#ff003c" stop-opacity="0" />
    </radialGradient>

    <!-- City Holographic Billboard Glow -->
    <radialGradient id="city-holo-billboard" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ff2e54" stop-opacity="0.3" />
      <stop offset="70%" stop-color="#ff003c" stop-opacity="0.08" />
      <stop offset="100%" stop-color="#ff003c" stop-opacity="0" />
    </radialGradient>

    <!-- Header Horizon Line Glow -->
    <linearGradient id="red-header-glow" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#ff003c" stop-opacity="0.95" />
      <stop offset="30%" stop-color="#ff2e54" stop-opacity="1" />
      <stop offset="65%" stop-color="#ff859c" stop-opacity="0.9" />
      <stop offset="100%" stop-color="#ff003c" stop-opacity="0.2" />
    </linearGradient>

    <!-- Dot Matrix Pattern for HUD / Glass -->
    <pattern id="hud-dot-grid" width="12" height="12" patternUnits="userSpaceOnUse">
      <rect x="0" y="0" width="1.2" height="1.2" fill="#ff003c" fill-opacity="0.1" />
    </pattern>

    <!-- Isometric 3D Grid Pattern -->
    <pattern id="iso-3d-grid" width="20" height="12" patternUnits="userSpaceOnUse">
      <path d="M 0 6 L 10 0 L 20 6 L 10 12 Z" fill="none" stroke="#ff003c" stroke-width="0.5" stroke-opacity="0.14" />
    </pattern>

    <!-- Skyscraper Window Grid Pattern -->
    <pattern id="skyscr-windows-1" width="8" height="12" patternUnits="userSpaceOnUse">
      <rect x="1" y="2" width="2" height="3" fill="#ff003c" fill-opacity="0.4" />
      <rect x="5" y="2" width="2" height="3" fill="#ffffff" fill-opacity="0.6" />
      <rect x="1" y="7" width="2" height="3" fill="#ff2e54" fill-opacity="0.3" />
      <rect x="5" y="7" width="2" height="3" fill="#ff003c" fill-opacity="0.25" />
    </pattern>
    <pattern id="skyscr-windows-2" width="6" height="10" patternUnits="userSpaceOnUse">
      <rect x="1" y="1" width="1.5" height="2" fill="#ff4d6d" fill-opacity="0.5" />
      <rect x="3.5" y="1" width="1.5" height="2" fill="#ff003c" fill-opacity="0.3" />
      <rect x="1" y="5" width="1.5" height="2" fill="#ffffff" fill-opacity="0.7" />
      <rect x="3.5" y="5" width="1.5" height="2" fill="#ff2e54" fill-opacity="0.4" />
    </pattern>

    <!-- Terminal Text Viewport Clip -->
    <clipPath id="red-terminal-clip">
      <rect x="36" y="118" width="232" height="142" rx="2" />
    </clipPath>

    <!-- Center Holo Stage Clip -->
    <clipPath id="holo-viewport-clip">
      <rect x="296" y="106" width="208" height="175" rx="4" />
    </clipPath>

    <!-- Glitch Slice Clip -->
    <clipPath id="glitch-slice-red">
      <rect x="0" y="2" width="480" height="20" />
    </clipPath>
  </defs>

  <!-- ============================================================== -->
  <!-- INLINE CSS STYLING & PURE CSS KEYFRAME ANIMATIONS              -->
  <!-- ============================================================== -->
  <style>
    /* System Monospace Typography */
    text {
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
      text-rendering: geometricPrecision;
      -webkit-font-smoothing: antialiased;
    }

    /* ------------------------------------------- */
    /* 1. CITY LIGHTS & TRAFFIC ANIMATIONS         */
    /* ------------------------------------------- */
    /* Spire Warning Beacons Blink */
    @keyframes beaconBlinkFast {
      0%, 45% { opacity: 0.2; }
      50%, 95% { opacity: 1; filter: drop-shadow(0 0 3px #ff003c); }
      100% { opacity: 0.2; }
    }
    @keyframes beaconBlinkAlt {
      0%, 40% { opacity: 1; filter: drop-shadow(0 0 4px #ff2e54); }
      45%, 90% { opacity: 0.15; }
      95%, 100% { opacity: 1; }
    }
    .beacon-1 { animation: beaconBlinkFast 1.4s ease-in-out infinite; }
    .beacon-2 { animation: beaconBlinkAlt 1.8s ease-in-out infinite; }

    /* Highway Skybridge Traffic Speed Streaks */
    @keyframes trafficStreamForward {
      0% { transform: translateX(-160px); }
      100% { transform: translateX(850px); }
    }
    @keyframes trafficStreamReverse {
      0% { transform: translateX(850px); }
      100% { transform: translateX(-160px); }
    }
    .traffic-lane-1 { animation: trafficStreamForward 5s linear infinite; }
    .traffic-lane-2 { animation: trafficStreamReverse 6.5s linear infinite; }

    /* Neon Billboard Kanji Glow Pulse */
    @keyframes billboardFlicker {
      0%, 100% { opacity: 0.95; filter: drop-shadow(0 0 6px #ff003c); }
      42% { opacity: 0.95; }
      43% { opacity: 0.4; }
      44% { opacity: 0.95; }
      78% { opacity: 0.95; }
      79% { opacity: 0.6; }
      80% { opacity: 0.95; }
      82% { opacity: 0.3; }
      83% { opacity: 0.95; }
    }
    .neon-billboard-pulse { animation: billboardFlicker 4s steps(1) infinite; }

    /* ------------------------------------------- */
    /* 2. DRONES IN FLIGHT & SEARCHLIGHT BEAMS     */
    /* ------------------------------------------- */
    /* Drone 1 (Main Patrol Gunship) Hover & Patrol Cruise */
    @keyframes dronePatrol1 {
      0% {
        transform: translate(0px, 0px);
      }
      25% {
        transform: translate(25px, -6px);
      }
      50% {
        transform: translate(45px, 3px);
      }
      75% {
        transform: translate(15px, 8px);
      }
      100% {
        transform: translate(0px, 0px);
      }
    }
    .drone-gunship-group {
      animation: dronePatrol1 7s ease-in-out infinite;
      transform-origin: 195px 145px;
    }

    /* Drone Searchlight Angled Sweep */
    @keyframes sweepSearchlight {
      0% {
        transform: rotate(-18deg);
      }
      50% {
        transform: rotate(24deg);
      }
      100% {
        transform: rotate(-18deg);
      }
    }
    .searchlight-sweeper {
      transform-origin: 195px 152px;
      animation: sweepSearchlight 5.5s ease-in-out infinite;
    }

    /* Drone 2 (High-Altitude Scout Drone) Fast Cruise */
    @keyframes droneScoutCruise {
      0% {
        transform: translate(0px, 0px);
      }
      50% {
        transform: translate(-35px, 12px);
      }
      100% {
        transform: translate(0px, 0px);
      }
    }
    .drone-scout-group {
      animation: droneScoutCruise 6s ease-in-out infinite;
      transform-origin: 620px 105px;
    }

    /* Drone Rotor / Thruster Heat Pulse */
    @keyframes thrusterGlow {
      0%, 100% { opacity: 0.6; transform: scaleY(0.9); }
      50% { opacity: 1; transform: scaleY(1.3); filter: drop-shadow(0 0 6px #ff003c); }
    }
    .thruster-pulse { animation: thrusterGlow 0.4s ease-in-out infinite; transform-origin: center; }

    /* ------------------------------------------- */
    /* 3. CITY FLOATING HOLOGRAMS                  */
    /* ------------------------------------------- */
    /* Floating 3D City Pyramid Hologram */
    @keyframes cityHoloRotate {
      0% { transform: perspective(300px) rotateY(0deg) rotateX(10deg); }
      50% { transform: perspective(300px) rotateY(180deg) rotateX(-10deg); }
      100% { transform: perspective(300px) rotateY(360deg) rotateX(10deg); }
    }
    .city-holo-pyramid {
      transform-origin: 110px 190px;
      animation: cityHoloRotate 10s linear infinite;
    }

    /* City Scanline Vertical Sweep */
    @keyframes cityHoloScan {
      0% { transform: translateY(-30px); opacity: 0; }
      20% { opacity: 0.9; }
      80% { opacity: 0.9; }
      100% { transform: translateY(110px); opacity: 0; }
    }
    .city-holo-scanline {
      animation: cityHoloScan 3s linear infinite;
    }

    /* ------------------------------------------- */
    /* 4. RED HUD CENTERPIECE: 3D CORE & TELEMETRY */
    /* ------------------------------------------- */
    /* HUD Core 3D Wireframe Tesseract/Cube Yaw & Pitch */
    @keyframes cube3DYaw {
      0% {
        transform: perspective(400px) rotateY(0deg) rotateX(16deg);
      }
      50% {
        transform: perspective(400px) rotateY(180deg) rotateX(-16deg);
      }
      100% {
        transform: perspective(400px) rotateY(360deg) rotateX(16deg);
      }
    }
    .hud-3d-cube {
      transform-origin: 400px 180px;
      animation: cube3DYaw 12s linear infinite;
    }

    /* HUD Floating Stage Bob */
    @keyframes hudFloatStage {
      0%, 100% { transform: translateY(0px); }
      50% { transform: translateY(-6px); }
    }
    .hud-stage-floating {
      animation: hudFloatStage 4s ease-in-out infinite;
      transform-origin: 400px 185px;
    }

    /* Pixel Art Hologram Core Glitch & Pulse */
    @keyframes pixelHoloPulse {
      0%, 92%, 100% { opacity: 0.92; transform: scale(1); }
      93% { opacity: 1; transform: scale(1.05) translate(-1px, 1px); filter: drop-shadow(0 0 6px #ff003c); }
      94% { opacity: 0.55; transform: scale(0.97) translate(2px, -1px); }
      95% { opacity: 0.95; transform: scale(1); }
    }
    .hud-pixel-core {
      transform-origin: 400px 180px;
      animation: pixelHoloPulse 4.2s ease-in-out infinite;
    }

    /* Rotating Telemetry Pie Chart */
    @keyframes rotateCW {
      from { transform: rotate(0deg); }
      to { transform: rotate(360deg); }
    }
    @keyframes rotateCCW {
      from { transform: rotate(360deg); }
      to { transform: rotate(0deg); }
    }
    .hud-pie-rotate {
      transform-origin: 651px 212px;
      animation: rotateCW 20s linear infinite;
    }
    .hud-ring-counter {
      transform-origin: 651px 212px;
      animation: rotateCCW 30s linear infinite;
    }

    /* Running Server Data Log Stream */
    @keyframes terminalLogStream {
      0% { transform: translateY(0px); }
      100% { transform: translateY(-136px); }
    }
    .hud-server-log-stream {
      animation: terminalLogStream 8.5s linear infinite;
    }

    /* Blinking Terminal Cursor */
    @keyframes blinkPrompt {
      0%, 49% { opacity: 1; }
      50%, 100% { opacity: 0; }
    }
    .prompt-cursor {
      animation: blinkPrompt 0.85s steps(1) infinite;
    }

    /* Chromatic Glitch Aberration */
    @keyframes glitchJitter {
      0%, 88%, 100% { transform: translate(0, 0); opacity: 1; }
      89% { transform: translate(-3px, 1px) skewX(-2deg); opacity: 0.9; }
      90% { transform: translate(4px, -1px) skewX(2deg); opacity: 0.75; }
      91% { transform: translate(-2px, 2px); opacity: 1; }
      92% { transform: translate(2px, 0px); opacity: 0.85; }
      93% { transform: translate(0, 0); opacity: 1; }
    }
    .hud-glitch-active {
      animation: glitchJitter 5s infinite ease-in-out;
    }

    @keyframes chromaticSplitL {
      0%, 88%, 100% { transform: translate(0, 0); opacity: 0; }
      89% { transform: translate(-5px, 1px); opacity: 0.9; }
      90% { transform: translate(3px, -2px); opacity: 0.85; }
      91% { transform: translate(-3px, 0); opacity: 0.7; }
      92% { transform: translate(0, 0); opacity: 0; }
    }
    .chromatic-l {
      animation: chromaticSplitL 5s infinite ease-in-out;
      fill: #ff003c;
    }

    @keyframes chromaticSplitR {
      0%, 88%, 100% { transform: translate(0, 0); opacity: 0; }
      89% { transform: translate(5px, -1px); opacity: 0.9; }
      90% { transform: translate(-3px, 2px); opacity: 0.85; }
      91% { transform: translate(3px, 0); opacity: 0.7; }
      92% { transform: translate(0, 0); opacity: 0; }
    }
    .chromatic-r {
      animation: chromaticSplitR 5s infinite ease-in-out;
      fill: #ff859c;
    }

    /* Stepped Pixel Equalizer Bars */
    @keyframes pxBar1 { 0%, 100% { height: 8px; y: 340px; } 50% { height: 28px; y: 320px; } }
    @keyframes pxBar2 { 0%, 100% { height: 24px; y: 324px; } 50% { height: 12px; y: 336px; } }
    @keyframes pxBar3 { 0%, 100% { height: 32px; y: 316px; } 50% { height: 18px; y: 330px; } }
    @keyframes pxBar4 { 0%, 100% { height: 14px; y: 334px; } 50% { height: 34px; y: 314px; } }
    .eq-b1 { animation: pxBar1 1.2s ease-in-out infinite; }
    .eq-b2 { animation: pxBar2 0.9s ease-in-out infinite; }
    .eq-b3 { animation: pxBar3 1.5s ease-in-out infinite; }
    .eq-b4 { animation: pxBar4 1.1s ease-in-out infinite; }

    /* Laser Scanner Line in 3D Core */
    @keyframes laserSweep {
      0% { transform: translateY(-40px); opacity: 0; }
      15% { opacity: 0.95; }
      85% { opacity: 0.95; }
      100% { transform: translateY(180px); opacity: 0; }
    }
    .laser-scan-vert {
      animation: laserSweep 3.2s cubic-bezier(0.4, 0, 0.2, 1) infinite;
    }
  </style>

  <!-- ============================================================== -->
  <!-- LAYER 1: DEEP ATMOSPHERIC NIGHT SKY & NEON HORIZON             -->
  <!-- ============================================================== -->
  <rect width="800" height="400" fill="url(#city-sky-gradient)" />

  <!-- Stars & High-Altitude Orbiting Satellites -->
  <g opacity="0.6">
    <circle cx="85" cy="22" r="0.8" fill="#ffffff" />
    <circle cx="140" cy="38" r="0.6" fill="#ffccd5" />
    <circle cx="210" cy="18" r="1" fill="#ffffff" />
    <circle cx="295" cy="30" r="0.7" fill="#ffffff" />
    <circle cx="480" cy="22" r="0.9" fill="#ff4d6d" />
    <circle cx="560" cy="35" r="0.6" fill="#ffffff" />
    <circle cx="680" cy="26" r="1" fill="#ffffff" />
    <circle cx="740" cy="40" r="0.7" fill="#ffccd5" />
    <!-- Distant Orbital Defense Grid Line -->
    <line x1="0" y1="28" x2="800" y2="28" stroke="#ff003c" stroke-width="0.3" stroke-dasharray="3,15" stroke-opacity="0.3" />
  </g>

  <!-- ============================================================== -->
  <!-- LAYER 2: BACKGROUND MEGALOPOLIS SILHOUETTES & TOWERS           -->
  <!-- ============================================================== -->
  <!-- Deep Background Silhouettes (Darkest Burgundy-Black, Spires & Beacons) -->
  <g opacity="0.85">
    <!-- Tower 1: Far Left Spire -->
    <path d="M 45 400 L 45 130 L 52 110 L 58 110 L 65 130 L 65 400 Z" fill="#0c0106" />
    <line x1="55" y1="110" x2="55" y2="78" stroke="#ff003c" stroke-width="0.8" />
    <circle cx="55" cy="78" r="2" fill="#ff003c" class="beacon-1" />

    <!-- Tower 2: Far Left Mega-Block -->
    <rect x="75" y="150" width="58" height="250" fill="#0f0208" />
    <line x1="104" y1="150" x2="104" y2="120" stroke="#ff003c" stroke-width="0.8" />
    <circle cx="104" cy="120" r="1.8" fill="#ff2e54" class="beacon-2" />

    <!-- Tower 3: Mid-Left Tower with Stepped Roof -->
    <path d="M 148 400 L 148 115 L 158 95 L 182 95 L 192 115 L 192 400 Z" fill="#13020a" />
    <line x1="170" y1="95" x2="170" y2="68" stroke="#ff2e54" stroke-width="1" />
    <circle cx="170" cy="68" r="2.2" fill="#ff003c" class="beacon-1" />

    <!-- Tower 4: Center Background Megastructure Spine -->
    <path d="M 360 400 L 360 110 L 375 75 L 425 75 L 440 110 L 440 400 Z" fill="#0d0107" />
    <line x1="400" y1="75" x2="400" y2="35" stroke="#ff003c" stroke-width="1.2" />
    <circle cx="400" cy="35" r="2.8" fill="#ffffff" class="beacon-1" />
    <line x1="390" y1="52" x2="410" y2="52" stroke="#ff003c" stroke-width="0.8" />

    <!-- Tower 5: Mid-Right Corporate Monolith -->
    <path d="M 520 400 L 520 120 L 540 100 L 585 100 L 600 120 L 600 400 Z" fill="#110209" />
    <line x1="562" y1="100" x2="562" y2="70" stroke="#ff003c" stroke-width="0.8" />
    <circle cx="562" cy="70" r="2" fill="#ff2e54" class="beacon-2" />

    <!-- Tower 6: Far Right Spire Tower -->
    <rect x="690" y="130" width="70" height="270" fill="#0e0107" />
    <line x1="725" y1="130" x2="725" y2="85" stroke="#ff003c" stroke-width="1" />
    <circle cx="725" cy="85" r="2.2" fill="#ff003c" class="beacon-1" />
  </g>

  <!-- ============================================================== -->
  <!-- LAYER 3: MIDGROUND SKYSCRAPERS WITH LIT WINDOW PATTERNS        -->
  <!-- ============================================================== -->
  <g>
    <!-- Midground Tower A (Left: x:85, w:50) -->
    <rect x="85" y="165" width="52" height="235" fill="#18030c" stroke="#360614" stroke-width="0.6" />
    <rect x="89" y="172" width="44" height="180" fill="url(#skyscr-windows-1)" opacity="0.6" />

    <!-- Midground Tower B with Angled Roof & Red Trim (x:195, w:65) -->
    <path d="M 195 400 L 195 145 L 235 125 L 260 145 L 260 400 Z" fill="#1b030e" stroke="#ff003c" stroke-width="0.7" stroke-opacity="0.6" />
    <rect x="202" y="152" width="50" height="190" fill="url(#skyscr-windows-2)" opacity="0.75" />
    <!-- Vertical Red Neon Facade Stripe -->
    <line x1="230" y1="130" x2="230" y2="360" stroke="#ff003c" stroke-width="1.2" stroke-opacity="0.8" />

    <!-- Midground Tower C (Center-Left: x:275, w:42) -->
    <rect x="275" y="180" width="42" height="220" fill="#15020a" stroke="#4a0618" stroke-width="0.6" />
    <rect x="278" y="186" width="36" height="150" fill="url(#skyscr-windows-1)" opacity="0.55" />

    <!-- Midground Tower D (Center-Right: x:478, w:45) -->
    <rect x="478" y="175" width="45" height="225" fill="#16020b" stroke="#4a0618" stroke-width="0.6" />
    <rect x="482" y="182" width="37" height="160" fill="url(#skyscr-windows-1)" opacity="0.55" />

    <!-- Midground Tower E (Right: x:615, w:68) -->
    <path d="M 615 400 L 615 138 L 650 120 L 685 138 L 685 400 Z" fill="#1a030d" stroke="#ff2e54" stroke-width="0.8" stroke-opacity="0.7" />
    <rect x="622" y="146" width="54" height="195" fill="url(#skyscr-windows-2)" opacity="0.7" />
    <line x1="650" y1="123" x2="650" y2="350" stroke="#ff2e54" stroke-width="1.2" stroke-opacity="0.8" />
  </g>

  <!-- ============================================================== -->
  <!-- LAYER 4: SKYBRIDGES & HIGHWAY SPEEDING TRAFFIC LIGHT STREAKS   -->
  <!-- ============================================================== -->
  <!-- Upper Skybridge linking Tower B and Tower C -->
  <g opacity="0.9">
    <rect x="137" y="210" width="58" height="9" fill="#20030e" stroke="#ff003c" stroke-width="0.8" />
    <line x1="137" y1="214.5" x2="195" y2="214.5" stroke="#ffffff" stroke-width="1.2" stroke-dasharray="3,3" />
    <!-- Skybridge Support Truss -->
    <path d="M 137 219 L 148 232 M 160 219 L 171 232 M 184 219 L 195 232" stroke="#5e0819" stroke-width="0.7" />
  </g>

  <!-- Massive Lower High-Speed Aerial Expressway (Spans x:0 to x:800 at y:342-358) -->
  <g>
    <!-- Highway Deck Infrastructure -->
    <rect x="0" y="342" width="800" height="14" fill="#16020a" stroke="#ff003c" stroke-width="0.9" stroke-opacity="0.8" />
    <!-- Highway Under-Deck Glow -->
    <line x1="0" y1="356" x2="800" y2="356" stroke="#ff003c" stroke-width="2" stroke-opacity="0.6" />

    <!-- Support Pillars -->
    <rect x="110" y="356" width="16" height="44" fill="#0d0106" stroke="#4a0618" stroke-width="0.8" />
    <rect x="330" y="356" width="16" height="44" fill="#0d0106" stroke="#4a0618" stroke-width="0.8" />
    <rect x="520" y="356" width="16" height="44" fill="#0d0106" stroke="#4a0618" stroke-width="0.8" />
    <rect x="710" y="356" width="16" height="44" fill="#0d0106" stroke="#4a0618" stroke-width="0.8" />

    <!-- Animated Traffic Stream 1: Forward Fast Light Streaks (West to East) -->
    <g class="traffic-lane-1">
      <line x1="-120" y1="346" x2="-20" y2="346" stroke="url(#traffic-streak-red)" stroke-width="2.5" stroke-linecap="round" />
      <line x1="80" y1="346" x2="170" y2="346" stroke="url(#traffic-streak-red)" stroke-width="2.2" stroke-linecap="round" />
      <line x1="280" y1="346" x2="380" y2="346" stroke="url(#traffic-streak-red)" stroke-width="2.8" stroke-linecap="round" />
      <line x1="500" y1="346" x2="610" y2="346" stroke="url(#traffic-streak-red)" stroke-width="2.2" stroke-linecap="round" />
    </g>

    <!-- Animated Traffic Stream 2: Reverse Light Streaks (East to West) -->
    <g class="traffic-lane-2">
      <line x1="120" y1="351" x2="20" y2="351" stroke="url(#traffic-streak-white)" stroke-width="2.2" stroke-linecap="round" />
      <line x1="330" y1="351" x2="220" y2="351" stroke="url(#traffic-streak-white)" stroke-width="2.6" stroke-linecap="round" />
      <line x1="550" y1="351" x2="430" y2="351" stroke="url(#traffic-streak-white)" stroke-width="2.2" stroke-linecap="round" />
      <line x1="780" y1="351" x2="660" y2="351" stroke="url(#traffic-streak-white)" stroke-width="2.5" stroke-linecap="round" />
    </g>
  </g>

  <!-- ============================================================== -->
  <!-- LAYER 5: NEON BILLBOARDS & FLOATING CITY HOLOGRAMS             -->
  <!-- ============================================================== -->
  <!-- City Neon Sign 1: Vertical Japanese Kanji Billboard on Tower A ("電脳都市" / Cyber City) -->
  <g transform="translate(96, 185)" class="neon-billboard-pulse">
    <rect x="-4" y="-4" width="22" height="66" fill="#1b0108" stroke="#ff003c" stroke-width="1.2" rx="2" />
    <text x="7" y="11" font-size="9" fill="#ffffff" font-weight="900" text-anchor="middle">電</text>
    <text x="7" y="25" font-size="9" fill="#ff003c" font-weight="900" text-anchor="middle">脳</text>
    <text x="7" y="39" font-size="9" fill="#ff2e54" font-weight="900" text-anchor="middle">都</text>
    <text x="7" y="53" font-size="9" fill="#ffffff" font-weight="900" text-anchor="middle">市</text>
  </g>

  <!-- City Neon Sign 2: Massive Horizontal Neon Billboard ("ARASAKA // 赤龍") on Tower E -->
  <g transform="translate(620, 155)" class="neon-billboard-pulse">
    <rect x="0" y="0" width="60" height="18" fill="#1d020a" stroke="#ff2e54" stroke-width="1" rx="1" />
    <text x="30" y="9" font-size="6" fill="#ffffff" font-weight="900" letter-spacing="1.5" text-anchor="middle">
      RED_CORP
    </text>
    <text x="30" y="16" font-size="5.5" fill="#ff003c" font-weight="800" text-anchor="middle">
      赤龍重工 [CYBER]
    </text>
  </g>

  <!-- Floating City Hologram 1: Rotating 3D Holographic Wireframe Diamond/Pyramid (Left Airspace) -->
  <g transform="translate(110, 105)">
    <!-- Radial Ambient Hologram Sphere -->
    <circle cx="0" cy="0" r="30" fill="url(#city-holo-billboard)" />
    <!-- Wireframe 3D Holographic Pyramid -->
    <g class="city-holo-pyramid">
      <polygon points="0,-18 16,0 0,18 -16,0" fill="#ff003c" fill-opacity="0.15" stroke="#ff003c" stroke-width="1" />
      <line x1="0" y1="-18" x2="0" y2="18" stroke="#ffffff" stroke-width="1.2" />
      <line x1="-16" y1="0" x2="16" y2="0" stroke="#ff2e54" stroke-width="0.8" />
      <polygon points="0,-12 10,0 0,12 -10,0" fill="none" stroke="#ffffff" stroke-width="0.7" stroke-dasharray="2,2" />
    </g>
    <!-- Holographic Emitter Projector Base on Skyscraper Roof -->
    <rect x="-8" y="24" width="16" height="6" fill="#24030c" stroke="#ff003c" stroke-width="0.8" />
    <!-- Projection Beam Lines -->
    <line x1="-6" y1="24" x2="-14" y2="5" stroke="#ff003c" stroke-width="0.5" stroke-dasharray="3,2" stroke-opacity="0.6" />
    <line x1="6" y1="24" x2="14" y2="5" stroke="#ff003c" stroke-width="0.5" stroke-dasharray="3,2" stroke-opacity="0.6" />
    <text x="0" y="38" font-size="5" fill="#ff859c" font-weight="700" letter-spacing="1" text-anchor="middle">
      [HOLO_AD: GEN-9]
    </text>
  </g>

  <!-- Floating City Hologram 2: Giant Cyber Eye / Recon Reticle (Right Airspace above Tower E) -->
  <g transform="translate(650, 95)">
    <circle cx="0" cy="0" r="28" fill="url(#city-holo-billboard)" />
    <ellipse cx="0" cy="0" rx="20" ry="10" fill="none" stroke="#ff003c" stroke-width="1" stroke-dasharray="4,2" />
    <circle cx="0" cy="0" r="6" fill="#ff003c" fill-opacity="0.3" stroke="#ffffff" stroke-width="1" />
    <circle cx="0" cy="0" r="2.5" fill="#ffffff" />
    <path d="M -22 -14 L -26 -14 L -26 -10" fill="none" stroke="#ff2e54" stroke-width="1" />
    <path d="M 22 -14 L 26 -14 L 26 -10" fill="none" stroke="#ff2e54" stroke-width="1" />
    <text x="0" y="18" font-size="5" fill="#ff2e54" font-weight="700" text-anchor="middle" letter-spacing="1">
      SECTOR_07 // SEC_LOCK
    </text>
  </g>

  <!-- ============================================================== -->
  <!-- LAYER 6: AUTONOMOUS CYBER DRONES IN FLIGHT                     -->
  <!-- ============================================================== -->
  <!-- DRONE 1: Tactical Patrol Gunship (Cruising Mid-Left Foreground) -->
  <g class="drone-gunship-group">
    <!-- Sweeping Searchlight Cone (Cuts through City Fog) -->
    <g class="searchlight-sweeper">
      <polygon points="195,153 140,340 280,340" fill="url(#searchlight-beam)" />
      <ellipse cx="210" cy="340" rx="70" ry="8" fill="#ff003c" fill-opacity="0.25" />
      <ellipse cx="210" cy="340" rx="35" ry="4" fill="#ffffff" fill-opacity="0.35" />
    </g>

    <!-- Gunship Chassis & Propulsion -->
    <g transform="translate(195, 145)">
      <!-- Twin Repulsor Jet Thrusters (Left & Right) with Flame Trails -->
      <g transform="translate(-24, 0)">
        <rect x="-3" y="-5" width="6" height="10" fill="#20030a" stroke="#ff003c" stroke-width="0.8" rx="1" />
        <ellipse cx="0" cy="7" rx="3.5" ry="6" fill="#ff003c" class="thruster-pulse" />
        <ellipse cx="0" cy="5" rx="1.8" ry="3" fill="#ffffff" />
      </g>
      <g transform="translate(24, 0)">
        <rect x="-3" y="-5" width="6" height="10" fill="#20030a" stroke="#ff003c" stroke-width="0.8" rx="1" />
        <ellipse cx="0" cy="7" rx="3.5" ry="6" fill="#ff003c" class="thruster-pulse" />
        <ellipse cx="0" cy="5" rx="1.8" ry="3" fill="#ffffff" />
      </g>

      <!-- Carbon Armor Main Hull -->
      <polygon points="0,-12 18,-3 15,6 0,10 -15,6 -18,-3" fill="#140106" stroke="#ff003c" stroke-width="1.4" />
      <!-- Hull Panel Seams & Neon Red Edge Lines -->
      <polygon points="0,-8 12,-2 10,4 0,7 -10,4 -12,-2" fill="#22030d" stroke="#ff2e54" stroke-width="0.8" />
      <line x1="-18" y1="-3" x2="18" y2="-3" stroke="#ffffff" stroke-width="0.8" />

      <!-- Sensor Turret / Ocular Pod (Underside) -->
      <circle cx="0" cy="7" r="4" fill="#ff003c" stroke="#ffffff" stroke-width="0.8" />
      <circle cx="0" cy="7" r="1.8" fill="#ffffff" />

      <!-- Drone Navigation LEDs -->
      <circle cx="-16" cy="-2" r="1.2" fill="#ff003c" class="beacon-1" />
      <circle cx="16" cy="-2" r="1.2" fill="#ffffff" class="beacon-2" />

      <!-- HUD Target Lock Frame around Drone 1 -->
      <g transform="translate(0, 0)">
        <path d="M -26 -16 L -30 -16 L -30 -12" fill="none" stroke="#ff003c" stroke-width="1.2" />
        <path d="M 26 -16 L 30 -16 L 30 -12" fill="none" stroke="#ff003c" stroke-width="1.2" />
        <path d="M -26 18 L -30 18 L -30 14" fill="none" stroke="#ff003c" stroke-width="1.2" />
        <path d="M 26 18 L 30 18 L 30 14" fill="none" stroke="#ff003c" stroke-width="1.2" />
        <!-- Telemetry Tag -->
        <text x="34" y="-8" font-size="6" fill="#ff2e54" font-weight="800">DRONE_ALPHA</text>
        <text x="34" y="0" font-size="5.5" fill="#ffffff" font-weight="700">SPD: 84 KM/H</text>
        <text x="34" y="8" font-size="5.5" fill="#ff6b8b">ALT: 184 M</text>
      </g>
    </g>
  </g>

  <!-- DRONE 2: High-Altitude Recon Seeker (Cruising Upper Right Airspace) -->
  <g class="drone-scout-group">
    <!-- Scanner Beam Downward Cone -->
    <polygon points="620,105 570,220 670,220" fill="url(#scanner-beam-2)" />

    <!-- Scout Drone Body -->
    <g transform="translate(620, 105)">
      <!-- Diamond Stealth Wing -->
      <polygon points="0,-7 14,0 0,6 -14,0" fill="#180209" stroke="#ff2e54" stroke-width="1" />
      <!-- Thruster Nozzle -->
      <rect x="-3" y="-8" width="6" height="3" fill="#ffffff" />
      <ellipse cx="0" cy="-10" rx="3" ry="4" fill="#ff003c" class="thruster-pulse" />

      <!-- Laser Scanner Pod -->
      <circle cx="0" cy="2" r="2.5" fill="#ff003c" stroke="#ffffff" stroke-width="0.6" />
      <circle cx="0" cy="2" r="1" fill="#ffffff" />

      <!-- Micro Navigation Beacons -->
      <circle cx="-13" cy="0" r="1" fill="#ff003c" class="beacon-2" />
      <circle cx="13" cy="0" r="1" fill="#ffffff" class="beacon-1" />

      <!-- Target Lock Reticle for Drone 2 -->
      <circle cx="0" cy="0" r="18" fill="none" stroke="#ff003c" stroke-width="0.8" stroke-dasharray="6,4" />
      <text x="22" y="-4" font-size="5.5" fill="#ffffff" font-weight="800">UAV_BETA</text>
      <text x="22" y="4" font-size="5" fill="#ff003c">RECON_PASS</text>
    </g>
  </g>

  <!-- Atmospheric Smog / Volumetric Red City Mist Overlay -->
  <rect width="800" height="400" fill="url(#crimson-smog)" pointer-events="none" />

  <!-- ============================================================== -->
  <!-- LAYER 7: THE CENTERPIECE — HIGH-END RED CYBERPUNK HUD OVERLAY   -->
  <!-- ============================================================== -->
  <!-- HUD Tactical Armor Perimeter & Corner Chamfers -->
  <path d="M 28 14 L 772 14 L 788 30 L 788 370 L 772 386 L 28 386 L 12 370 L 12 30 Z"
        fill="none" stroke="#ff003c" stroke-width="1.6" stroke-opacity="0.95" />

  <!-- Secondary Inner Dashed Tech Armor Border -->
  <path d="M 34 22 L 766 22 L 780 36 L 780 364 L 766 378 L 34 378 L 20 364 L 20 36 Z"
        fill="none" stroke="#5e0819" stroke-width="0.75" stroke-dasharray="10,5" stroke-opacity="0.85" />

  <!-- 4 Corner Precision Brackets (Pixel Art + Vector Hybrid) -->
  <!-- Top-Left Bracket -->
  <path d="M 12 55 L 12 30 L 30 12 L 65 12" fill="none" stroke="#ff003c" stroke-width="2.5" />
  <rect x="18" y="18" width="4" height="4" fill="#ffffff" />
  <rect x="23" y="18" width="2" height="2" fill="#ff003c" />
  <rect x="18" y="23" width="2" height="2" fill="#ff003c" />
  <line x1="30" y1="12" x2="30" y2="6" stroke="#ff003c" stroke-width="1" />
  <line x1="45" y1="12" x2="45" y2="7" stroke="#ff003c" stroke-width="1" />
  <line x1="60" y1="12" x2="60" y2="7" stroke="#ff003c" stroke-width="1" />

  <!-- Top-Right Bracket -->
  <path d="M 735 12 L 770 12 L 788 30 L 788 55" fill="none" stroke="#ff003c" stroke-width="2.5" />
  <rect x="778" y="18" width="4" height="4" fill="#ffffff" />
  <rect x="775" y="18" width="2" height="2" fill="#ff003c" />
  <rect x="780" y="23" width="2" height="2" fill="#ff003c" />
  <line x1="770" y1="12" x2="770" y2="6" stroke="#ff003c" stroke-width="1" />
  <line x1="755" y1="12" x2="755" y2="7" stroke="#ff003c" stroke-width="1" />
  <line x1="740" y1="12" x2="740" y2="7" stroke="#ff003c" stroke-width="1" />

  <!-- Bottom-Left Bracket -->
  <path d="M 12 345 L 12 370 L 30 388 L 65 388" fill="none" stroke="#ff003c" stroke-width="2.5" />
  <rect x="18" y="378" width="4" height="4" fill="#ffffff" />
  <line x1="30" y1="388" x2="30" y2="394" stroke="#ff003c" stroke-width="1" />
  <line x1="45" y1="388" x2="45" y2="393" stroke="#ff003c" stroke-width="1" />

  <!-- Bottom-Right Bracket -->
  <path d="M 735 388 L 770 388 L 788 370 L 788 345" fill="none" stroke="#ff003c" stroke-width="2.5" />
  <rect x="778" y="378" width="4" height="4" fill="#ffffff" />
  <line x1="770" y1="388" x2="770" y2="394" stroke="#ff003c" stroke-width="1" />
  <line x1="755" y1="388" x2="755" y2="393" stroke="#ff003c" stroke-width="1" />

  <!-- Top Center Header Trapezoid Module -->
  <path d="M 130 14 L 142 27 L 358 27 L 370 14 Z" fill="#1b030a" stroke="#ff003c" stroke-width="1" />
  <line x1="150" y1="20.5" x2="350" y2="20.5" stroke="#ff2e54" stroke-width="1" stroke-dasharray="6,4" />
  <text x="250" y="22.5" text-anchor="middle" font-size="7.5" fill="#ffffff" font-weight="800" letter-spacing="2">
    NEO_CITY_TACTICAL // RED_OVERDRIVE [GEN-IX]
  </text>

  <!-- Top Right Badges -->
  <rect x="620" y="20" width="56" height="12" fill="#1b030a" stroke="#ff003c" stroke-width="0.8" />
  <rect x="624" y="24" width="4" height="4" fill="#ff003c" class="beacon-1" />
  <text x="632" y="29" font-size="6.5" fill="#ffffff" font-weight="700" letter-spacing="1">CITY_LIVE</text>

  <rect x="682" y="20" width="62" height="12" fill="#1b030a" stroke="#ff2e54" stroke-width="0.8" />
  <rect x="686" y="24" width="4" height="4" fill="#ffffff" />
  <text x="694" y="29" font-size="6.5" fill="#ffccd5" font-weight="700" letter-spacing="1">UAV_AIRSPACE</text>

  <!-- Header Horizon Glow Divider Line -->
  <line x1="38" y1="66" x2="762" y2="66" stroke="url(#red-header-glow)" stroke-width="1.8" />
  <line x1="38" y1="69" x2="762" y2="69" stroke="#ff003c" stroke-width="0.6" stroke-dasharray="24,6,4,6" />

  <!-- Focal Glitch Header Title -->
  <g transform="translate(42, 53)">
    <!-- Chromatic Red Splice -->
    <g class="chromatic-l" clip-path="url(#glitch-slice-red)">
      <text x="0" y="0" font-size="16" font-weight="900" letter-spacing="2.6">
        // CYBERPUNK_CITY_OVERWATCH [RECON_ACTIVE]
      </text>
    </g>
    <!-- Chromatic Ember Splice -->
    <g class="chromatic-r" clip-path="url(#glitch-slice-red)">
      <text x="0" y="0" font-size="16" font-weight="900" letter-spacing="2.6">
        // CYBERPUNK_CITY_OVERWATCH [RECON_ACTIVE]
      </text>
    </g>
    <!-- Main Header -->
    <g class="hud-glitch-active">
      <text x="0" y="0" font-size="16" fill="#ffffff" font-weight="900" letter-spacing="2.6">
        // CYBERPUNK_CITY_OVERWATCH <tspan fill="#ff003c">[RECON_ACTIVE]</tspan> <tspan fill="#ff859c">:: GRID_LOCKED</tspan>
      </text>
      <!-- Tech Slice Ribbon Indicator -->
      <line x1="0" y1="4" x2="440" y2="4" stroke="#ff003c" stroke-width="1" stroke-dasharray="16,6,4,6" opacity="0.85" />
      <rect x="450" y="-12" width="68" height="15" fill="#ff003c" fill-opacity="0.25" stroke="#ff003c" stroke-width="1" />
      <rect x="453" y="-9" width="3" height="3" fill="#ffffff" />
      <text x="484" y="-1.5" text-anchor="middle" font-size="7.5" fill="#ffffff" font-weight="900" letter-spacing="1">
        HIGH-END
      </text>
    </g>
  </g>

  <!-- ============================================================== -->
  <!-- 7A. LEFT HUD MODULE: RUNNING SERVER LOG TERMINAL               -->
  <!-- ============================================================== -->
  <g transform="translate(32, 78)">
    <!-- Semi-Transparent Chamfered HUD Console Glass Backing -->
    <path d="M 0 0 L 236 0 L 252 16 L 252 278 L 236 294 L 0 294 Z"
          fill="url(#hud-glass-grad)" stroke="#ff003c" stroke-width="1.2" />

    <!-- Terminal Header Bar -->
    <path d="M 0 0 L 236 0 L 252 16 L 252 24 L 0 24 Z" fill="#26040d" stroke="#ff003c" stroke-width="0.8" />
    <rect x="8" y="7" width="8" height="8" fill="#ff003c" />
    <rect x="10" y="9" width="4" height="4" fill="#ffffff" />
    <text x="24" y="16" font-size="7.5" fill="#ffccd5" font-weight="800" letter-spacing="1.5">
      DAEMON://CITY_STREAM_01
    </text>
    <text x="188" y="16" font-size="6.5" fill="#ff003c" font-weight="800">
      52.8 TB/S
    </text>

    <!-- Sub-Header Metadata -->
    <line x1="8" y1="33" x2="244" y2="33" stroke="#5e0819" stroke-width="0.8" stroke-dasharray="4,4" />
    <text x="8" y="30" font-size="6" fill="#9e2a3f" letter-spacing="1">
      DRONE_SURVEILLANCE: ONLINE | UAV_LOCK: 2 | SMOG: 32%
    </text>

    <!-- Terminal Screen Inner Viewport -->
    <rect x="6" y="38" width="240" height="147" fill="#090104" fill-opacity="0.85" stroke="#5e0819" stroke-width="0.6" rx="2" />

    <!-- Running Server Log Text (Seamless 136px Infinite Loop) -->
    <g clip-path="url(#red-terminal-clip)">
      <g class="hud-server-log-stream">
        <!-- Cycle 1 (8 Lines * 17px = 136px) -->
        <text x="12" y="52" font-size="6.8" fill="#ff2e54">[0x7F41] <tspan fill="#ffffff">SYS_ROOT:</tspan> NEO_CITY AIRSPACE ENCRYPTED</text>
        <text x="12" y="69" font-size="6.8" fill="#ffffff">[0x7F48] <tspan fill="#ff003c">DRONE_01:</tspan> PATROL GUNSHIP ACTIVE [195,145]</text>
        <text x="12" y="86" font-size="6.8" fill="#ff6b8b">[0x7F50] <tspan fill="#9e2a3f">SECTOR_07:</tspan> SEARCHLIGHT SWEEP BEAM LOCKED</text>
        <text x="12" y="103" font-size="6.8" fill="#ff003c">[0x7F58] <tspan fill="#ffffff">HOLO_BILLBOARD:</tspan> KANJI SIGN SYNC 99.4%</text>
        <text x="12" y="120" font-size="6.8" fill="#ffffff">[0x7F60] <tspan fill="#ff2e54">SKYBRIDGE:</tspan> TRAFFIC HIGH-SPEED CRUISE</text>
        <text x="12" y="137" font-size="6.8" fill="#ff2e54">[0x7F68] <tspan fill="#9e2a3f">DRONE_02:</tspan> HIGH-ALTITUDE SEEKER DETECTED</text>
        <text x="12" y="154" font-size="6.8" fill="#ff003c">[0x7F70] <tspan fill="#ffffff">FIREWALL:</tspan> RED_OVERDRIVE SHIELD ARMED</text>
        <text x="12" y="171" font-size="6.8" fill="#ffffff">[0x7F78] <tspan fill="#ff6b8b">RECON_FEED:</tspan> 0xAA49F00 TELEMETRY VERIFIED</text>

        <!-- Cycle 2 (Seamless Repeat) -->
        <text x="12" y="188" font-size="6.8" fill="#ff2e54">[0x7F41] <tspan fill="#ffffff">SYS_ROOT:</tspan> NEO_CITY AIRSPACE ENCRYPTED</text>
        <text x="12" y="205" font-size="6.8" fill="#ffffff">[0x7F48] <tspan fill="#ff003c">DRONE_01:</tspan> PATROL GUNSHIP ACTIVE [195,145]</text>
        <text x="12" y="222" font-size="6.8" fill="#ff6b8b">[0x7F50] <tspan fill="#9e2a3f">SECTOR_07:</tspan> SEARCHLIGHT SWEEP BEAM LOCKED</text>
        <text x="12" y="239" font-size="6.8" fill="#ff003c">[0x7F58] <tspan fill="#ffffff">HOLO_BILLBOARD:</tspan> KANJI SIGN SYNC 99.4%</text>
        <text x="12" y="256" font-size="6.8" fill="#ffffff">[0x7F60] <tspan fill="#ff2e54">SKYBRIDGE:</tspan> TRAFFIC HIGH-SPEED CRUISE</text>
        <text x="12" y="273" font-size="6.8" fill="#ff2e54">[0x7F68] <tspan fill="#9e2a3f">DRONE_02:</tspan> HIGH-ALTITUDE SEEKER DETECTED</text>
        <text x="12" y="290" font-size="6.8" fill="#ff003c">[0x7F70] <tspan fill="#ffffff">FIREWALL:</tspan> RED_OVERDRIVE SHIELD ARMED</text>
        <text x="12" y="307" font-size="6.8" fill="#ffffff">[0x7F78] <tspan fill="#ff6b8b">RECON_FEED:</tspan> 0xAA49F00 TELEMETRY VERIFIED</text>
      </g>
    </g>

    <!-- Blinking Prompt -->
    <rect x="12" y="174" width="6" height="8" fill="#ff003c" class="prompt-cursor" />
    <text x="24" y="181" font-size="6.8" fill="#ff6b8b" letter-spacing="1">
      LISTENING://CITY_GRID_RECON_
    </text>

    <!-- Lower Status Metrics inside Left Panel -->
    <line x1="8" y1="196" x2="244" y2="196" stroke="#5e0819" stroke-width="0.8" />
    <text x="8" y="209" font-size="6.5" fill="#ff2e54" font-weight="700" letter-spacing="1">
      AIRSPACE DENSITY INDEX
    </text>
    <text x="218" y="209" font-size="6.5" fill="#ffffff" font-weight="800">
      94.2%
    </text>

    <!-- Segmented Red Progress Gauge -->
    <rect x="8" y="214" width="236" height="6" fill="#140207" stroke="#5e0819" stroke-width="0.5" rx="1" />
    <rect x="10" y="215.5" width="186" height="3" fill="#ff003c" />
    <rect x="200" y="215.5" width="22" height="3" fill="#ffffff" />

    <!-- 3 Micro Telemetry Cards -->
    <g transform="translate(8, 228)">
      <rect x="0" y="0" width="74" height="26" fill="#180309" stroke="#ff003c" stroke-width="0.6" />
      <text x="5" y="10" font-size="5.5" fill="#9e2a3f">UAV_BAND</text>
      <text x="5" y="21" font-size="7" fill="#ffffff" font-weight="800">8.42 GHZ</text>

      <rect x="80" y="0" width="74" height="26" fill="#180309" stroke="#ff2e54" stroke-width="0.6" />
      <text x="85" y="10" font-size="5.5" fill="#9e2a3f">LASER_LOCK</text>
      <text x="85" y="21" font-size="7" fill="#ff003c" font-weight="800">100% REL</text>

      <rect x="160" y="0" width="76" height="26" fill="#180309" stroke="#ff003c" stroke-width="0.6" />
      <text x="165" y="10" font-size="5.5" fill="#9e2a3f">GRID_DEF</text>
      <text x="165" y="21" font-size="7" fill="#ffccd5" font-weight="800">ARMED</text>
    </g>

    <text x="8" y="280" font-size="6" fill="#9e2a3f" letter-spacing="1">
      HASH: 0xCITY_RED_88F_ALPHA :: SEC_CLEARANCE_OK
    </text>
  </g>

  <!-- ============================================================== -->
  <!-- 7B. CENTER HUD MODULE: 3D MODERN ANIMATION & PIXEL ART CORE    -->
  <!-- ============================================================== -->
  <g transform="translate(296, 78)">
    <!-- Chamfered Framing Glass Panel -->
    <path d="M 0 0 L 194 0 L 208 14 L 208 278 L 194 294 L 0 294 Z"
          fill="url(#hud-glass-grad)" stroke="#ff003c" stroke-width="1.2" />

    <!-- Center Module Header Bar -->
    <rect x="0" y="0" width="208" height="20" fill="#24030c" stroke="#ff003c" stroke-width="0.8" />
    <rect x="8" y="6" width="7" height="7" fill="#ffffff" />
    <text x="22" y="14" font-size="7.5" fill="#ffffff" font-weight="800" letter-spacing="1.5">
      3D_HOLO_CORE // CITY_TARGET
    </text>
    <rect x="178" y="5" width="22" height="10" fill="#ff003c" fill-opacity="0.25" stroke="#ff003c" stroke-width="0.8" />
    <text x="189" y="12.5" text-anchor="middle" font-size="6" fill="#ffffff" font-weight="800">3D</text>

    <!-- 3D Perspective Hologram Stage Viewport -->
    <g clip-path="url(#holo-viewport-clip)">
      <!-- Radial Hologram Light Core Glow -->
      <circle cx="104" cy="105" r="75" fill="url(#holo-glow)" />

      <!-- Isometric 3D Background Grid Planes -->
      <rect x="0" y="20" width="208" height="160" fill="url(#iso-3d-grid)" opacity="0.45" />

      <!-- 3D FLOATING & ROTATING WIREFRAME ASSEMBLY -->
      <g class="hud-stage-floating">
        <!-- Concentric Perspective Ellipses -->
        <ellipse cx="104" cy="105" rx="68" ry="24" fill="none" stroke="#ff003c" stroke-width="1.2" stroke-dasharray="14,6,4,6" opacity="0.85" />
        <ellipse cx="104" cy="105" rx="58" ry="18" fill="none" stroke="#ff2e54" stroke-width="0.8" stroke-dasharray="6,4" opacity="0.75" />

        <!-- 3D ROTATING ISOMETRIC WIREFRAME TESSERACT / CUBE -->
        <g class="hud-3d-cube">
          <!-- Top Isometric Facet -->
          <polygon points="104,65 138,82 104,98 70,82" fill="#ff003c" fill-opacity="0.12" stroke="#ff003c" stroke-width="1.5" />
          <!-- Left Isometric Facet -->
          <polygon points="70,82 104,98 104,142 70,126" fill="#ff003c" fill-opacity="0.22" stroke="#ff2e54" stroke-width="1.5" />
          <!-- Right Isometric Facet -->
          <polygon points="104,98 138,82 138,126 104,142" fill="#ff003c" fill-opacity="0.18" stroke="#ff003c" stroke-width="1.5" />

          <!-- Inner 3D Axis Connecting Rods -->
          <line x1="104" y1="98" x2="104" y2="142" stroke="#ffffff" stroke-width="1.2" />
          <line x1="104" y1="65" x2="104" y2="98" stroke="#ff6b8b" stroke-width="1" stroke-dasharray="3,2" />

          <!-- 3D Corner Vertex Pixel Nodes -->
          <rect x="102" y="63" width="4" height="4" fill="#ffffff" />
          <rect x="136" y="80" width="4" height="4" fill="#ff003c" />
          <rect x="68" y="80" width="4" height="4" fill="#ff003c" />
          <rect x="102" y="96" width="4" height="4" fill="#ffffff" />
          <rect x="136" y="124" width="4" height="4" fill="#ffffff" />
          <rect x="68" y="124" width="4" height="4" fill="#ffffff" />
          <rect x="102" y="140" width="4" height="4" fill="#ff003c" />
        </g>

        <!-- PIXEL ART CYBER-CORE / SKULL HOLOGRAM (Center of 3D Matrix) -->
        <g transform="translate(86, 88)" class="hud-pixel-core">
          <!-- Forehead Pixel Row -->
          <rect x="9" y="0" width="18" height="3" fill="#ffffff" />
          <rect x="6" y="3" width="24" height="3" fill="#ff003c" />
          <rect x="3" y="6" width="30" height="3" fill="#ff2e54" />

          <!-- Eye Socket Row with Hollow Centers -->
          <rect x="3" y="9" width="6" height="6" fill="#ff003c" />
          <rect x="15" y="9" width="6" height="6" fill="#ffffff" />
          <rect x="27" y="9" width="6" height="6" fill="#ff003c" />
          <!-- Eye Laser Pixels -->
          <rect x="10.5" y="10.5" width="3" height="3" fill="#ff003c" />
          <rect x="22.5" y="10.5" width="3" height="3" fill="#ff003c" />

          <!-- Cheekbone & Nose Pixels -->
          <rect x="6" y="15" width="24" height="3" fill="#ff2e54" />
          <rect x="15" y="18" width="6" height="3" fill="#ffffff" />

          <!-- Cyber Teeth Pixel Grid -->
          <rect x="9" y="22" width="4" height="5" fill="#ffffff" />
          <rect x="16" y="22" width="4" height="5" fill="#ffffff" />
          <rect x="23" y="22" width="4" height="5" fill="#ffffff" />

          <!-- Peripheral Pixel Spark Nodes -->
          <rect x="0" y="12" width="2" height="2" fill="#ff6b8b" />
          <rect x="34" y="12" width="2" height="2" fill="#ff6b8b" />
        </g>

        <!-- Laser Scanline Sweeper -->
        <g class="laser-scan-vert">
          <line x1="20" y1="50" x2="188" y2="50" stroke="#ffffff" stroke-width="1.8" />
          <line x1="20" y1="51" x2="188" y2="51" stroke="#ff003c" stroke-width="4" stroke-opacity="0.4" />
          <rect x="100" y="48.5" width="8" height="3" fill="#ffffff" />
        </g>
      </g>

      <!-- Center Calibration Crosshairs -->
      <line x1="12" y1="105" x2="38" y2="105" stroke="#ff003c" stroke-width="1" />
      <line x1="170" y1="105" x2="196" y2="105" stroke="#ff003c" stroke-width="1" />
      <line x1="104" y1="28" x2="104" y2="44" stroke="#ff003c" stroke-width="1" />
      <line x1="104" y1="166" x2="104" y2="182" stroke="#ff003c" stroke-width="1" />

      <!-- Corner Markers -->
      <path d="M 8 32 L 8 24 L 16 24" fill="none" stroke="#ffffff" stroke-width="1.5" />
      <path d="M 200 32 L 200 24 L 192 24" fill="none" stroke="#ffffff" stroke-width="1.5" />
      <path d="M 8 168 L 8 176 L 16 176" fill="none" stroke="#ffffff" stroke-width="1.5" />
      <path d="M 200 168 L 200 176 L 192 176" fill="none" stroke="#ffffff" stroke-width="1.5" />
    </g>

    <!-- Lower Section: 3D Euler Readout & Pixel Equalizer -->
    <g transform="translate(10, 192)">
      <!-- 3D Euler Coordinates -->
      <rect x="0" y="0" width="188" height="24" fill="#140207" stroke="#5e0819" stroke-width="0.6" />
      <text x="8" y="10" font-size="6" fill="#9e2a3f">3D_CITY_RECON_MATRIX</text>
      <text x="8" y="19" font-size="6.8" fill="#ffffff" font-weight="700">
        AZIMUTH: <tspan fill="#ff003c">284.5°</tspan> | ELEV: <tspan fill="#ff2e54">+12.4°</tspan> | RANGE: <tspan fill="#ffffff">1.8 KM</tspan>
      </text>

      <!-- Pixel Art Equalizer Visualizer -->
      <g transform="translate(4, 28)">
        <text x="0" y="0" font-size="6" fill="#ff2e54" font-weight="700">
          RADAR_SPECTRUM [UAV]
        </text>

        <!-- Stepped Animated Bars -->
        <g transform="translate(24, -266)">
          <rect x="0" y="324" width="16" height="20" fill="#ff003c" rx="1" class="eq-b1" />
          <rect x="24" y="324" width="16" height="20" fill="#ff2e54" rx="1" class="eq-b2" />
          <rect x="48" y="324" width="16" height="20" fill="#ffffff" rx="1" class="eq-b3" />
          <rect x="72" y="324" width="16" height="20" fill="#ff003c" rx="1" class="eq-b4" />
          <rect x="96" y="324" width="16" height="20" fill="#ff859c" rx="1" class="eq-b1" />
          <rect x="120" y="324" width="16" height="20" fill="#ff2e54" rx="1" class="eq-b2" />
        </g>
      </g>
    </g>
  </g>

  <!-- ============================================================== -->
  <!-- 7C. RIGHT HUD MODULE: ROTATING PIE & TELEMETRY DONUT CHART     -->
  <!-- ============================================================== -->
  <g transform="translate(518, 78)">
    <!-- Right Panel Chamfered Glass Container -->
    <path d="M 0 0 L 236 0 L 252 16 L 252 278 L 236 294 L 16 294 L 0 278 Z"
          fill="url(#hud-glass-grad)" stroke="#ff003c" stroke-width="1.2" />

    <!-- Module Header -->
    <path d="M 0 0 L 236 0 L 252 16 L 252 24 L 0 24 Z" fill="#24030c" stroke="#ff003c" stroke-width="0.8" />
    <rect x="8" y="7" width="8" height="8" fill="#ffffff" />
    <rect x="10" y="9" width="4" height="4" fill="#ff003c" />
    <text x="24" y="16" font-size="7.5" fill="#ffffff" font-weight="800" letter-spacing="1.5">
      CORE_TELEMETRY // RES_CHART
    </text>
    <text x="198" y="16" font-size="6.5" fill="#ff003c" font-weight="800">
      ARMED
    </text>

    <!-- Sub-Header Status -->
    <text x="12" y="33" font-size="6" fill="#9e2a3f" letter-spacing="1">
      SECTOR_DISTRIBUTION // NEO_CITY
    </text>
    <line x1="8" y1="37" x2="244" y2="37" stroke="#ff003c" stroke-width="0.6" stroke-dasharray="6,4" />

    <!-- Static Decorative Outer Calibration Rings -->
    <!-- Center in canvas coordinates is (651, 212) -> relative is (133, 134) -->
    <g transform="translate(133, 134)">
      <circle cx="0" cy="0" r="77" fill="none" stroke="#5e0819" stroke-width="1" stroke-dasharray="2,6" />
      <circle cx="0" cy="0" r="72" fill="none" stroke="#ff003c" stroke-width="0.8" stroke-opacity="0.5" />
      <circle cx="0" cy="0" r="83" fill="none" stroke="#ff2e54" stroke-width="0.5" stroke-dasharray="16,8" opacity="0.6" />

      <!-- Quadrant Degree Markers -->
      <text x="0" y="-85" text-anchor="middle" font-size="6" fill="#9e2a3f" font-weight="700">000°</text>
      <text x="90" y="2" text-anchor="start" font-size="6" fill="#9e2a3f" font-weight="700">090°</text>
      <text x="0" y="91" text-anchor="middle" font-size="6" fill="#9e2a3f" font-weight="700">180°</text>
      <text x="-90" y="2" text-anchor="end" font-size="6" fill="#9e2a3f" font-weight="700">270°</text>

      <!-- Center Reticle & Percentage Readout -->
      <circle cx="0" cy="0" r="33" fill="#140207" stroke="#5e0819" stroke-width="1" />
      <circle cx="0" cy="0" r="29" fill="#20030a" stroke="#ff003c" stroke-width="0.6" stroke-dasharray="4,2" />
      <text x="0" y="-4" text-anchor="middle" font-size="11.5" fill="#ffffff" font-weight="900" letter-spacing="1">
        88.6%
      </text>
      <text x="0" y="8" text-anchor="middle" font-size="5.5" fill="#ff003c" font-weight="800" letter-spacing="1">
        CITY_GRID
      </text>
      <line x1="-16" y1="13" x2="16" y2="13" stroke="#ffffff" stroke-width="0.8" />
    </g>

    <!-- Counter-Rotating Segmented Ring -->
    <g class="hud-ring-counter">
      <circle cx="651" cy="212" r="78" fill="none" stroke="#ff003c" stroke-width="1.8"
              stroke-dasharray="28,16,8,16,40,12" stroke-opacity="0.9" />
      <circle cx="651" cy="212" r="81" fill="none" stroke="#ffffff" stroke-width="0.75"
              stroke-dasharray="4,12,32,8" stroke-opacity="0.75" />
    </g>

    <!-- ROTATING 4-SECTOR PIE / DONUT CHART IN RED PALETTE (FR-3) -->
    <g class="hud-pie-rotate">
      <!-- Sector 1: Electric Scarlet Arc (Angle 15° to 110°, span 95°) -->
      <path d="M 712.82 228.56 A 64 64 0 0 1 629.11 272.14 L 638.01 247.71 A 38 38 0 0 0 687.70 221.83 Z"
            fill="#ff003c" fill-opacity="0.9" stroke="#ffffff" stroke-width="0.8" />

      <!-- Sector 2: Crimson Ruby Arc (Angle 125° to 215°, span 90°) -->
      <path d="M 614.29 264.43 A 64 64 0 0 1 598.57 175.29 L 619.87 190.20 A 38 38 0 0 0 629.20 243.13 Z"
            fill="#c9002b" fill-opacity="0.88" stroke="#ff2e54" stroke-width="0.8" />

      <!-- Sector 3: Ember Red Arc (Angle 230° to 290°, span 60°) -->
      <path d="M 609.86 162.97 A 64 64 0 0 1 672.89 151.86 L 664.00 176.29 A 38 38 0 0 0 626.57 182.89 Z"
            fill="#ff2e54" fill-opacity="0.92" stroke="#ff003c" stroke-width="0.8" />

      <!-- Sector 4: Bloodline Dark Red Arc (Angle 305° to 360°, span 55°) -->
      <path d="M 687.71 159.57 A 64 64 0 0 1 715.00 212.00 L 689.00 212.00 A 38 38 0 0 0 672.80 180.87 Z"
            fill="#800318" fill-opacity="0.95" stroke="#ff859c" stroke-width="0.8" />

      <!-- Sector Gap Dividers -->
      <line x1="651" y1="212" x2="715" y2="212" stroke="#060103" stroke-width="2.5" />
      <line x1="651" y1="212" x2="634" y2="273" stroke="#060103" stroke-width="2.5" />
      <line x1="651" y1="212" x2="596" y2="179" stroke="#060103" stroke-width="2.5" />
      <line x1="651" y1="212" x2="671" y2="150" stroke="#060103" stroke-width="2.5" />
    </g>

    <!-- Fictional Pie Chart Legend -->
    <g transform="translate(18, 228)">
      <rect x="0" y="0" width="6" height="6" fill="#ff003c" />
      <text x="12" y="6" font-size="6.5" fill="#ffffff" font-weight="700">CITY_UAV</text>
      <text x="74" y="6" font-size="6.5" fill="#ff003c" font-weight="800">42.1%</text>

      <rect x="110" y="0" width="6" height="6" fill="#c9002b" />
      <text x="122" y="6" font-size="6.5" fill="#ffffff" font-weight="700">NEURAL_NET</text>
      <text x="186" y="6" font-size="6.5" fill="#ff2e54" font-weight="800">31.8%</text>

      <rect x="0" y="14" width="6" height="6" fill="#ff2e54" />
      <text x="12" y="20" font-size="6.5" fill="#ffffff" font-weight="700">SMOG_SHIELD</text>
      <text x="74" y="20" font-size="6.5" fill="#ff859c" font-weight="800">15.6%</text>

      <rect x="110" y="14" width="6" height="6" fill="#800318" />
      <text x="122" y="20" font-size="6.5" fill="#ffffff" font-weight="700">TRANSIT_RES</text>
      <text x="186" y="20" font-size="6.5" fill="#ffffff" font-weight="800">10.5%</text>
    </g>

    <text x="18" y="280" font-size="6" fill="#9e2a3f" letter-spacing="1">
      ROTATION: 20s/REV :: CLOCKWISE
    </text>
  </g>

  <!-- ============================================================== -->
  <!-- 8. BOTTOM STATUS RIBBON & TARGETING RETICLE OVERLAYS           -->
  <!-- ============================================================== -->
  <line x1="38" y1="362" x2="762" y2="362" stroke="#5e0819" stroke-width="0.8" />
  <line x1="260" y1="362" x2="540" y2="362" stroke="#ff003c" stroke-width="1.8" />

  <g transform="translate(42, 375)">
    <text x="0" y="0" font-size="7" fill="#9e2a3f" letter-spacing="1.5">
      SEC_CLEARANCE: <tspan fill="#ff003c" font-weight="800">LEVEL_RED_ALPHA</tspan>
    </text>
    <text x="250" y="0" font-size="7" fill="#ffffff" font-weight="800" letter-spacing="2">
      STATUS: [NEO_CITY_SCENE // DRONES_TRACKED // 3D_HOLO_SYNCED]
    </text>
    <text x="640" y="0" font-size="7" fill="#ff2e54" letter-spacing="1.5">
      SCENE: <tspan fill="#ffffff" font-weight="800">ACTIVE</tspan>
    </text>
  </g>
</svg>
