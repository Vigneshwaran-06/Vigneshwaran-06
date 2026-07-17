<svg width="1180" height="610" viewBox="0 0 1180 610" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background Gradients -->
    <radialGradient id="bgGlow1" cx="20%" cy="30%">
      <stop offset="0%" style="stop-color:#7C3AED;stop-opacity:0.15">
        <animate attributeName="stop-opacity" values="0.15;0.25;0.15" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#030712;stop-opacity:0"/>
    </radialGradient>
    
    <radialGradient id="bgGlow2" cx="80%" cy="70%">
      <stop offset="0%" style="stop-color:#22D3EE;stop-opacity:0.12">
        <animate attributeName="stop-opacity" values="0.12;0.22;0.12" dur="5s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#030712;stop-opacity:0"/>
    </radialGradient>
    
    <radialGradient id="bgGlow3" cx="50%" cy="50%">
      <stop offset="0%" style="stop-color:#10B981;stop-opacity:0.08">
        <animate attributeName="stop-opacity" values="0.08;0.15;0.08" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#030712;stop-opacity:0"/>
    </radialGradient>

    <!-- ASCII Gradient (Animated) -->
    <linearGradient id="asciiGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#22D3EE">
        <animate attributeName="stop-color" values="#22D3EE;#7C3AED;#10B981;#22D3EE" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" style="stop-color:#7C3AED">
        <animate attributeName="stop-color" values="#7C3AED;#10B981;#22D3EE;#7C3AED" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#10B981">
        <animate attributeName="stop-color" values="#10B981;#22D3EE;#7C3AED;#10B981" dur="8s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <!-- Accent Gradient -->
    <linearGradient id="accentGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#7C3AED"/>
      <stop offset="50%" style="stop-color:#22D3EE"/>
      <stop offset="100%" style="stop-color:#10B981"/>
    </linearGradient>

    <!-- Glow Filters -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <filter id="strongGlow">
      <feGaussianBlur stdDeviation="8" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Noise Texture -->
    <filter id="noise">
      <feTurbulence type="fractalNoise" baseFrequency="0.9" numOctaves="4" stitchTiles="stitch"/>
      <feColorMatrix type="saturate" values="0"/>
      <feComponentTransfer>
        <feFuncA type="discrete" tableValues="0 0 0 0.02"/>
      </feComponentTransfer>
      <feBlend mode="overlay" in2="SourceGraphic"/>
    </filter>

    <!-- Border Shimmer -->
    <linearGradient id="shimmer" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:rgba(255,255,255,0)"/>
      <stop offset="50%" style="stop-color:rgba(255,255,255,0.2)">
        <animate attributeName="offset" values="0;1;0" dur="3s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:rgba(255,255,255,0)"/>
    </linearGradient>

    <!-- Scanline -->
    <linearGradient id="scanline" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:rgba(34,211,238,0)"/>
      <stop offset="50%" style="stop-color:rgba(34,211,238,0.3)"/>
      <stop offset="100%" style="stop-color:rgba(34,211,238,0)"/>
      <animateTransform attributeName="gradientTransform" type="translate" values="0 -1; 0 2" dur="4s" repeatCount="indefinite"/>
    </linearGradient>
  </defs>

  <!-- Background -->
  <rect width="1180" height="610" rx="24" fill="#030712"/>
  <rect width="1180" height="610" rx="24" fill="url(#bgGlow1)"/>
  <rect width="1180" height="610" rx="24" fill="url(#bgGlow2)"/>
  <rect width="1180" height="610" rx="24" fill="url(#bgGlow3)"/>
  <rect width="1180" height="610" rx="24" fill="url(#noise)" opacity="0.5"/>

  <!-- Floating Particles -->
  <circle cx="150" cy="100" r="2" fill="#22D3EE" opacity="0.4">
    <animate attributeName="cy" values="100;80;100" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.8;0.4" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="320" cy="450" r="1.5" fill="#7C3AED" opacity="0.3">
    <animate attributeName="cy" values="450;430;450" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="900" cy="120" r="2" fill="#10B981" opacity="0.4">
    <animate attributeName="cy" values="120;100;120" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.8;0.4" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="1050" cy="480" r="1.5" fill="#22D3EE" opacity="0.3">
    <animate attributeName="cy" values="480;460;480" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="4.5s" repeatCount="indefinite"/>
  </circle>

  <!-- LEFT SECTION - ASCII Portrait -->
  <g id="leftSection">
    <!-- Glass Panel -->
    <rect x="40" y="40" width="408" height="530" rx="16" fill="#0F172A" opacity="0.6"/>
    <rect x="40" y="40" width="408" height="530" rx="16" fill="none" stroke="rgba(255,255,255,0.08)" stroke-width="1"/>
    <rect x="40" y="40" width="408" height="530" rx="16" stroke="url(#shimmer)" stroke-width="1.5" fill="none"/>
    
    <!-- ASCII Art Container -->
    <g transform="translate(80, 100)" filter="url(#strongGlow)">
      <text font-family="'Courier New', monospace" font-size="10" fill="url(#asciiGrad)" letter-spacing="0">
        <tspan x="0" y="0" opacity="0">    @@@@@@@@@@@@</tspan>
        <tspan x="0" y="12" opacity="0">  @@@@@@@@@@@@@@@@</tspan>
        <tspan x="0" y="24" opacity="0"> @@@@@@    @@@@@@@@</tspan>
        <tspan x="0" y="36" opacity="0">@@@@@@  @@  @@@@@@@@</tspan>
        <tspan x="0" y="48" opacity="0">@@@@@@  @@  @@@@@@@@</tspan>
        <tspan x="0" y="60" opacity="0">@@@@@@      @@@@@@@@</tspan>
        <tspan x="0" y="72" opacity="0"> @@@@@@    @@@@@@@@</tspan>
        <tspan x="0" y="84" opacity="0">  @@@@@@@@@@@@@@@@</tspan>
        <tspan x="0" y="96" opacity="0">    @@@@@@@@@@@@</tspan>
        <tspan x="0" y="108" opacity="0">  @@@@@@@@@@@@@@</tspan>
        <tspan x="0" y="120" opacity="0"> @@@@@@@@@@@@@@@@</tspan>
        <tspan x="0" y="132" opacity="0">@@@@@@@@@@@@@@@@@@</tspan>
        <tspan x="0" y="144" opacity="0">@@@@@      @@@@@@@</tspan>
        <tspan x="0" y="156" opacity="0">@@@@        @@@@@@</tspan>
        <tspan x="0" y="168" opacity="0">@@@          @@@@@</tspan>
        <tspan x="0" y="180" opacity="0">@@            @@@@</tspan>
        <tspan x="0" y="192" opacity="0">@              @@@</tspan>
        
        <animate attributeName="opacity" values="0;0;1" dur="0.3s" fill="freeze" begin="0s"/>
      </text>
      
      <!-- Line-by-line reveal animation -->
      <animate attributeName="opacity" values="0;1" dur="0.1s" fill="freeze"/>
    </g>

    <!-- Reveal lines sequentially -->
    <style>
      @keyframes revealLine {
        from { opacity: 0; }
        to { opacity: 1; }
      }
      tspan:nth-child(1) { animation: revealLine 0.1s 0.1s forwards; }
      tspan:nth-child(2) { animation: revealLine 0.1s 0.2s forwards; }
      tspan:nth-child(3) { animation: revealLine 0.1s 0.3s forwards; }
      tspan:nth-child(4) { animation: revealLine 0.1s 0.4s forwards; }
      tspan:nth-child(5) { animation: revealLine 0.1s 0.5s forwards; }
      tspan:nth-child(6) { animation: revealLine 0.1s 0.6s forwards; }
      tspan:nth-child(7) { animation: revealLine 0.1s 0.7s forwards; }
      tspan:nth-child(8) { animation: revealLine 0.1s 0.8s forwards; }
      tspan:nth-child(9) { animation: revealLine 0.1s 0.9s forwards; }
      tspan:nth-child(10) { animation: revealLine 0.1s 1.0s forwards; }
      tspan:nth-child(11) { animation: revealLine 0.1s 1.1s forwards; }
      tspan:nth-child(12) { animation: revealLine 0.1s 1.2s forwards; }
      tspan:nth-child(13) { animation: revealLine 0.1s 1.3s forwards; }
      tspan:nth-child(14) { animation: revealLine 0.1s 1.4s forwards; }
      tspan:nth-child(15) { animation: revealLine 0.1s 1.5s forwards; }
      tspan:nth-child(16) { animation: revealLine 0.1s 1.6s forwards; }
      tspan:nth-child(17) { animation: revealLine 0.1s 1.7s forwards; }
    </style>

    <!-- Floating effect for ASCII -->
    <animateTransform attributeName="transform" type="translate" values="0 0; 0 -5; 0 0" dur="4s" repeatCount="indefinite"/>
    
    <!-- Scanline Effect -->
    <rect x="40" y="40" width="408" height="4" fill="url(#scanline)" opacity="0.3">
      <animate attributeName="y" values="40;570;40" dur="4s" repeatCount="indefinite"/>
    </rect>

    <!-- Cursor Blink -->
    <rect x="320" y="420" width="12" height="18" fill="#22D3EE" opacity="0.8">
      <animate attributeName="opacity" values="0;1;0" dur="1s" repeatCount="indefinite"/>
    </rect>
  </g>

  <!-- RIGHT SECTION - Terminal Window -->
  <g id="rightSection">
    <!-- Glass Panel -->
    <rect x="488" y="40" width="652" height="530" rx="16" fill="#0F172A" opacity="0.6"/>
    <rect x="488" y="40" width="652" height="530" rx="16" fill="none" stroke="rgba(255,255,255,0.08)" stroke-width="1"/>
    <rect x="488" y="40" width="652" height="530" rx="16" stroke="url(#shimmer)" stroke-width="1.5" fill="none"/>
    
    <!-- Terminal Header -->
    <circle cx="508" cy="60" r="5" fill="#FF5F56"/>
    <circle cx="528" cy="60" r="5" fill="#FFBD2E"/>
    <circle cx="548" cy="60" r="5" fill="#27C93F"/>
    
    <!-- Content -->
    <g transform="translate(528, 110)">
      <!-- Greeting -->
      <text font-family="'Inter', -apple-system, system-ui, sans-serif" font-size="24" font-weight="600" fill="#F8FAFC">
        <tspan x="0" y="0">Hi 👋 I'm </tspan>
        <tspan fill="url(#accentGrad)" filter="url(#glow)">Vigneshwaran</tspan>
      </text>

      <!-- Animated Role Text -->
      <text font-family="'Fira Code', 'Courier New', monospace" font-size="18" fill="#22D3EE" font-weight="500">
        <tspan x="0" y="45" opacity="0">
          &gt; Full Stack Developer_
          <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.2;0.8;1" dur="12s" repeatCount="indefinite"/>
        </tspan>
        <tspan x="0" y="45" opacity="0">
          &gt; Open Source Contributor_
          <animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.33;0.4;0.6;0.66;1" dur="12s" repeatCount="indefinite"/>
        </tspan>
        <tspan x="0" y="45" opacity="0">
          &gt; UI Engineer_
          <animate attributeName="opacity" values="0;0;0;0;1;1;0" keyTimes="0;0.66;0.73;0.8;0.86;0.93;1" dur="12s" repeatCount="indefinite"/>
        </tspan>
      </text>

      <!-- Info Section -->
      <g transform="translate(0, 100)">
        <text font-family="'Inter', sans-serif" font-size="14" fill="#94A3B8">
          <tspan x="0" y="0" opacity="0">📍 Location
            <animate attributeName="opacity" values="0;1" dur="0.5s" begin="2s" fill="freeze"/>
          </tspan>
          <tspan x="150" y="0" fill="#F8FAFC" opacity="0">India
            <animate attributeName="opacity" values="0;1" dur="0.5s" begin="2.1s" fill="freeze"/>
          </tspan>

          <tspan x="0" y="30" opacity="0">🎓 Education
            <animate attributeName="opacity" values="0;1" dur="0.5s" begin="2.3s" fill="freeze"/>
          </tspan>
          <tspan x="150" y="30" fill="#F8FAFC" opacity="0">Computer Science
            <animate attributeName="opacity" values="0;1" dur="0.5s" begin="2.4s" fill="freeze"/>
          </tspan>

          <tspan x="0" y="60" opacity="0">💻 Focus
            <animate attributeName="opacity" values="0;1" dur="0.5s" begin="2.6s" fill="freeze"/>
          </tspan>
          <tspan x="150" y="60" fill="#F8FAFC" opacity="0">Web Development
            <animate attributeName="opacity" values="0;1" dur="0.5s" begin="2.7s" fill="freeze"/>
          </tspan>

          <tspan x="0" y="90" opacity="0">🌐 Portfolio
            <animate attributeName="opacity" values="0;1" dur="0.5s" begin="2.9s" fill="freeze"/>
          </tspan>
          <tspan x="150" y="90" fill="#22D3EE" opacity="0">vigneshwaran.dev
            <animate attributeName="opacity" values="0;1" dur="0.5s" begin="3.0s" fill="freeze"/>
          </tspan>

          <tspan x="0" y="120" opacity="0">📧 Email
            <animate attributeName="opacity" values="0;1" dur="0.5s" begin="3.2s" fill="freeze"/>
          </tspan>
          <tspan x="150" y="120" fill="#F8FAFC" opacity="0">hello@vigneshwaran.dev
            <animate attributeName="opacity" values="0;1" dur="0.5s" begin="3.3s" fill="freeze"/>
          </tspan>
        </text>
      </g>

      <!-- Skills Section -->
      <g transform="translate(0, 260)">
        <text font-family="'Inter', sans-serif" font-size="16" font-weight="600" fill="#F8FAFC" opacity="0">
          <tspan x="0" y="0">Skills</tspan>
          <animate attributeName="opacity" values="0;1" dur="0.5s" begin="3.5s" fill="freeze"/>
        </text>

        <!-- Skill Pills Row 1 -->
        <g transform="translate(0, 25)" opacity="0">
          <rect x="0" y="0" width="70" height="28" rx="14" fill="#7C3AED" fill-opacity="0.2" stroke="#7C3AED" stroke-width="1" filter="url(#glow)"/>
          <text x="35" y="19" font-family="'Inter', sans-serif" font-size="12" fill="#C4B5FD" text-anchor="middle">React</text>
          <animate attributeName="opacity" values="0;1" dur="0.3s" begin="3.7s" fill="freeze"/>
        </g>

        <g transform="translate(80, 25)" opacity="0">
          <rect x="0" y="0" width="75" height="28" rx="14" fill="#22D3EE" fill-opacity="0.2" stroke="#22D3EE" stroke-width="1" filter="url(#glow)"/>
          <text x="37.5" y="19" font-family="'Inter', sans-serif" font-size="12" fill="#67E8F9" text-anchor="middle">Next.js</text>
          <animate attributeName="opacity" values="0;1" dur="0.3s" begin="3.8s" fill="freeze"/>
        </g>

        <g transform="translate(165, 25)" opacity="0">
          <rect x="0" y="0" width="75" height="28" rx="14" fill="#10B981" fill-opacity="0.2" stroke="#10B981" stroke-width="1" filter="url(#glow)"/>
          <text x="37.5" y="19" font-family="'Inter', sans-serif" font-size="12" fill="#6EE7B7" text-anchor="middle">Node.js</text>
          <animate attributeName="opacity" values="0;1" dur="0.3s" begin="3.9s" fill="freeze"/>
        </g>

        <g transform="translate(250, 25)" opacity="0">
          <rect x="0" y="0" width="90" height="28" rx="14" fill="#7C3AED" fill-opacity="0.2" stroke="#7C3AED" stroke-width="1" filter="url(#glow)"/>
          <text x="45" y="19" font-family="'Inter', sans-serif" font-size="12" fill="#C4B5FD" text-anchor="middle">TypeScript</text>
          <animate attributeName="opacity" values="0;1" dur="0.3s" begin="4.0s" fill="freeze"/>
        </g>

        <g transform="translate(350, 25)" opacity="0">
          <rect x="0" y="0" width="75" height="28" rx="14" fill="#22D3EE" fill-opacity="0.2" stroke="#22D3EE" stroke-width="1" filter="url(#glow)"/>
          <text x="37.5" y="19" font-family="'Inter', sans-serif" font-size="12" fill="#67E8F9" text-anchor="middle">Tailwind</text>
          <animate attributeName="opacity" values="0;1" dur="0.3s" begin="4.1s" fill="freeze"/>
        </g>

        <!-- Skill Pills Row 2 -->
        <g transform="translate(0, 63)" opacity="0">
          <rect x="0" y="0" width="70" height="28" rx="14" fill="#10B981" fill-opacity="0.2" stroke="#10B981" stroke-width="1" filter="url(#glow)"/>
          <text x="35" y="19" font-family="'Inter', sans-serif" font-size="12" fill="#6EE7B7" text-anchor="middle">Python</text>
          <animate attributeName="opacity" values="0;1" dur="0.3s" begin="4.2s" fill="freeze"/>
        </g>

        <g transform="translate(80, 63)" opacity="0">
          <rect x="0" y="0" width="70" height="28" rx="14" fill="#7C3AED" fill-opacity="0.2" stroke="#7C3AED" stroke-width="1" filter="url(#glow)"/>
          <text x="35" y="19" font-family="'Inter', sans-serif" font-size="12" fill="#C4B5FD" text-anchor="middle">Docker</text>
          <animate attributeName="opacity" values="0;1" dur="0.3s" begin="4.3s" fill="freeze"/>
        </g>

        <g transform="translate(160, 63)" opacity="0">
          <rect x="0" y="0" width="80" height="28" rx="14" fill="#22D3EE" fill-opacity="0.2" stroke="#22D3EE" stroke-width="1" filter="url(#glow)"/>
          <text x="40" y="19" font-family="'Inter', sans-serif" font-size="12" fill="#67E8F9" text-anchor="middle">MongoDB</text>
          <animate attributeName="opacity" values="0;1" dur="0.3s" begin="4.4s" fill="freeze"/>
        </g>

        <g transform="translate(250, 63)" opacity="0">
          <rect x="0" y="0" width="60" height="28" rx="14" fill="#10B981" fill-opacity="0.2" stroke="#10B981" stroke-width="1" filter="url(#glow)"/>
          <text x="30" y="19" font-family="'Inter', sans-serif" font-size="12" fill="#6EE7B7" text-anchor="middle">AWS</text>
          <animate attributeName="opacity" values="0;1" dur="0.3s" begin="4.5s" fill="freeze"/>
        </g>

        <g transform="translate(320, 63)" opacity="0">
          <rect x="0" y="0" width="50" height="28" rx="14" fill="#7C3AED" fill-opacity="0.2" stroke="#7C3AED" stroke-width="1" filter="url(#glow)"/>
          <text x="25" y="19" font-family="'Inter', sans-serif" font-size="12" fill="#C4B5FD" text-anchor="middle">Git</text>
          <animate attributeName="opacity" values="0;1" dur="0.3s" begin="4.6s" fill="freeze"/>
        </g>

        <g transform="translate(380, 63)" opacity="0">
          <rect x="0" y="0" width="65" height="28" rx="14" fill="#22D3EE" fill-opacity="0.2" stroke="#22D3EE" stroke-width="1" filter="url(#glow)"/>
          <text x="32.5" y="19" font-family="'Inter', sans-serif" font-size="12" fill="#67E8F9" text-anchor="middle">Figma</text>
          <animate attributeName="opacity" values="0;1" dur="0.3s" begin="4.7s" fill="freeze"/>
        </g>
      </g>

      <!-- Social Icons -->
      <g transform="translate(0, 390)">
        <!-- GitHub -->
        <g opacity="0">
          <circle cx="20" cy="20" r="20" fill="#22D3EE" fill-opacity="0.1" stroke="#22D3EE" stroke-width="1" filter="url(#glow)"/>
          <path d="M20,10 c-5.5,0-10,4.5-10,10 c0,4.4,2.9,8.2,6.8,9.5 c0.5,0.1,0.7-0.2,0.7-0.5 c0-0.2,0-0.9,0-1.7 c-2.8,0.6-3.4-1.3-3.4-1.3 c-0.5-1.1-1.1-1.4-1.1-1.4 c-0.9-0.6,0.1-0.6,0.1-0.6 c1,0.1,1.5,1,1.5,1 c0.9,1.5,2.3,1.1,2.9,0.8 c0.1-0.6,0.3-1.1,0.6-1.3 c-2.2-0.3-4.6-1.1-4.6-4.9 c0-1.1,0.4-2,1-2.7 c-0.1-0.2-0.4-1.2,0.1-2.5 c0,0,0.8-0.3,2.7,1 c0.8-0.2,1.7-0.3,2.5-0.3 c0.9,0,1.7,0.1,2.5,0.3 c1.9-1.3,2.7-1,2.7-1 c0.5,1.3,0.2,2.3,0.1,2.5 c0.6,0.7,1,1.6,1,2.7 c0,3.8-2.3,4.7-4.6,4.9 c0.4,0.3,0.7,0.9,0.7,1.9 c0,1.4,0,2.5,0,2.8 c0,0.3,0.2,0.6,0.7,0.5 C27.1,28.2,30,24.4,30,20 C30,14.5,25.5,10,20,10z" fill="#22D3EE"/>
          <animate attributeName="opacity" values="0;1" dur="0.3s" begin="4.9s" fill="freeze"/>
        </g>

        <!-- LinkedIn -->
        <g transform="translate(60, 0)" opacity="0">
          <circle cx="20" cy="20" r="20" fill="#7C3AED" fill-opacity="0.1" stroke="#7C3AED" stroke-width="1" filter="url(#glow)"/>
          <path d="M15,13 h-3 v10 h3 V13z M13.5,11.5 c1,0,1.8-0.8,1.8-1.8 s-0.8-1.7-1.8-1.7 s-1.8,0.8-1.8,1.8 S12.5,11.5,13.5,11.5z M28,23 h-3 v-5 c0-1.2-0.5-2-1.5-2 c-1.1,0-1.5,0.8-1.5,2 v5 h-3 v-10 h3 v1.4 c0.4-0.7,1.3-1.6,2.8-1.6 c2.1,0,3.2,1.4,3.2,4 V23z" fill="#7C3AED"/>
          <animate attributeName="opacity" values="0;1" dur="0.3s" begin="5.0s" fill="freeze"/>
        </g>

        <!-- Twitter -->
        <g transform="translate(120, 0)" opacity="0">
          <circle cx="20" cy="20" r="20" fill="#10B981" fill-opacity="0.1" stroke="#10B981" stroke-width="1" filter="url(#glow)"/>
          <path d="M28,12 c-0.8,0.4-1.6,0.6-2.5,0.7 c0.9-0.5,1.6-1.4,1.9-2.4 c-0.8,0.5-1.8,0.9-2.8,1.1 c-0.8-0.9-2-1.4-3.3-1.4 c-2.5,0-4.5,2-4.5,4.5 c0,0.4,0,0.7,0.1,1 c-3.7-0.2-7-2-9.2-4.7 c-0.4,0.7-0.6,1.4-0.6,2.3 c0,1.6,0.8,3,2,3.8 c-0.7,0-1.4-0.2-2-0.5 v0.1 c0,2.2,1.6,4,3.6,4.4 c-0.4,0.1-0.8,0.2-1.2,0.2 c-0.3,0-0.6,0-0.9-0.1 c0.6,1.9,2.4,3.3,4.5,3.3 c-1.6,1.3-3.7,2-5.9,2 c-0.4,0-0.8,0-1.1-0.1 c2,1.3,4.4,2,7,2 c8.4,0,13-7,13-13 v-0.6 C26.6,13.7,27.4,12.9,28,12z" fill="#10B981"/>
          <animate attributeName="opacity" values="0;1" dur="0.3s" begin="5.1s" fill="freeze"/>
        </g>

        <!-- Portfolio -->
        <g transform="translate(180, 0)" opacity="0">
          <circle cx="20" cy="20" r="20" fill="#22D3EE" fill-opacity="0.1" stroke="#22D3EE" stroke-width="1" filter="url(#glow)"/>
          <path d="M12,13 h16 v10 a2,2 0 0,1 -2,2 h-12 a2,2 0 0,1 -2,-2 v-10z M14,13 v-2 a2,2 0 0,1 2,-2 h8 a2,2 0 0,1 2,2 v2 M20,17 v4" fill="none" stroke="#22D3EE" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
          <animate attributeName="opacity" values="0;1" dur="0.3s" begin="5.2s" fill="freeze"/>
        </g>
      </g>
    </g>
  </g>

  <!-- Glass Reflection -->
  <rect x="40" y="40" width="1100" height="250" rx="16" fill="url(#shimmer)" opacity="0.03"/>
</svg>
