<svg width="1000" height="380" viewBox="0 0 1000 380" xmlns="http://www.w3.org/2000/svg" font-family="'Segoe UI', Helvetica, Arial, sans-serif">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#0b1220"/>
      <stop offset="1" stop-color="#14304a"/>
    </linearGradient>
    <linearGradient id="txt" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#36BCF7"/>
      <stop offset="1" stop-color="#a78bfa"/>
    </linearGradient>
    <filter id="blur" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="45"/>
    </filter>
    <pattern id="dots" width="26" height="26" patternUnits="userSpaceOnUse">
      <circle cx="2" cy="2" r="1.2" fill="#ffffff" opacity="0.08"/>
    </pattern>
    <clipPath id="clip"><rect width="1000" height="380" rx="22"/></clipPath>
  </defs>

  <g clip-path="url(#clip)">
    <rect width="1000" height="380" fill="url(#bg)"/>
    <rect width="1000" height="380" fill="url(#dots)"/>

    <circle cx="860" cy="50" r="130" fill="#36BCF7" opacity="0.35" filter="url(#blur)">
      <animate attributeName="opacity" values="0.25;0.5;0.25" dur="6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="90" cy="350" r="120" fill="#8b5cf6" opacity="0.32" filter="url(#blur)">
      <animate attributeName="opacity" values="0.45;0.22;0.45" dur="7s" repeatCount="indefinite"/>
    </circle>

    <!-- Status pill -->
    <rect x="60" y="62" width="214" height="30" rx="15" fill="#10b981" opacity="0.14" stroke="#10b981" stroke-opacity="0.5"/>
    <circle cx="80" cy="77" r="5" fill="#10b981">
      <animate attributeName="opacity" values="1;0.25;1" dur="1.8s" repeatCount="indefinite"/>
    </circle>
    <text x="94" y="82" font-size="12" font-weight="600" fill="#6ee7b7" letter-spacing="1.2">OPEN TO OPPORTUNITIES</text>

    <!-- Text -->
    <text x="60" y="140" font-size="22" fill="#9db4cc">Hi, I'm</text>
    <text x="60" y="190" font-size="42" font-weight="800" fill="url(#txt)">Arlindo Soares Pereira</text>
    <text x="60" y="230" font-size="24" font-weight="600" fill="#ffffff">Full-Stack Software Developer</text>
    <text x="60" y="266" font-size="15" fill="#36BCF7" font-family="'Fira Code', Consolas, monospace">Python  ·  Django  ·  React  ·  PostgreSQL</text>

    <!-- Buttons -->
    <rect x="60" y="298" width="170" height="46" rx="23" fill="url(#txt)"/>
    <text x="145" y="327" font-size="15" font-weight="700" fill="#0b1220" text-anchor="middle">View My Work</text>
    <rect x="246" y="299" width="168" height="44" rx="22" fill="none" stroke="#36BCF7" stroke-opacity="0.7" stroke-width="1.5"/>
    <text x="330" y="327" font-size="15" font-weight="600" fill="#e2f4ff" text-anchor="middle">Get In Touch</text>

    <!-- Floating code window -->
    <g>
      <animateTransform attributeName="transform" type="translate" values="0,0;0,-10;0,0" dur="5s" repeatCount="indefinite"/>
      <rect x="610" y="62" width="330" height="256" rx="16" fill="#0a1424" stroke="#2a4466" stroke-width="1.2"/>
      <rect x="610" y="62" width="330" height="36" rx="16" fill="#12223a"/>
      <rect x="610" y="82" width="330" height="16" fill="#12223a"/>
      <circle cx="634" cy="80" r="6" fill="#ff5f57"/>
      <circle cx="654" cy="80" r="6" fill="#febc2e"/>
      <circle cx="674" cy="80" r="6" fill="#28c840"/>
      <text x="775" y="84" font-size="11" fill="#6b84a3" font-family="'Fira Code', Consolas, monospace">developer.py</text>

      <g font-family="'Fira Code', Consolas, monospace" font-size="14">
        <text x="632" y="128"><tspan fill="#c084fc">class</tspan><tspan fill="#fbbf24"> Developer</tspan><tspan fill="#9db4cc">:</tspan></text>
        <text x="652" y="156"><tspan fill="#7dd3fc">name</tspan><tspan fill="#9db4cc"> = </tspan><tspan fill="#86efac">"Arlindo"</tspan></text>
        <text x="652" y="182"><tspan fill="#7dd3fc">role</tspan><tspan fill="#9db4cc"> = </tspan><tspan fill="#86efac">"Full-Stack"</tspan></text>
        <text x="652" y="208"><tspan fill="#7dd3fc">stack</tspan><tspan fill="#9db4cc"> = [</tspan><tspan fill="#86efac">"Django"</tspan><tspan fill="#9db4cc">,</tspan></text>
        <text x="716" y="232"><tspan fill="#86efac">"React"</tspan><tspan fill="#9db4cc">,</tspan><tspan fill="#86efac"> "PostgreSQL"</tspan><tspan fill="#9db4cc">]</tspan></text>
        <text x="652" y="264"><tspan fill="#c084fc">def</tspan><tspan fill="#60a5fa"> build</tspan><tspan fill="#9db4cc">(self):</tspan></text>
        <text x="672" y="290"><tspan fill="#c084fc">return</tspan><tspan fill="#86efac"> "great apps"</tspan></text>
      </g>
      <rect x="826" y="276" width="8" height="18" fill="#36BCF7">
        <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
      </rect>
    </g>
  </g>
</svg>
