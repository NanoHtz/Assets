<!-- assets/banner.svg | pipex (rehecho y ajustado al viewBox) -->
<svg xmlns="http://www.w3.org/2000/svg" width="1280" height="360" viewBox="0 0 1280 360" role="img" aria-labelledby="t d">
  <title id="t">pipex — Pipes &amp; redirections in C (dup2, execve, heredoc)</title>
  <desc id="d">Banner oscuro con diagrama cmd1 | cmd2 &gt; outfile y variantes; todo dentro del lienzo.</desc>

  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#1a1b27"/><stop offset="100%" stop-color="#15161e"/>
    </linearGradient>
    <style>
      .title{font:700 56px/1.1 Inter,Segoe UI,Roboto,Arial,sans-serif;fill:#70a5fd}
      .tag{font:500 20px/1.4 Inter,Segoe UI,Roboto,Arial,sans-serif;fill:#c0caf5}
      .mono{font:600 16px/1.35 "JetBrains Mono","Fira Code",Menlo,Consolas,monospace;fill:#c0caf5}
      .tube{fill:none;stroke:#7aa2f7;stroke-width:8;stroke-linecap:round;opacity:.9}
    </style>
    <marker id="arr" markerWidth="10" markerHeight="10" refX="7" refY="3" orient="auto">
      <path d="M0,0 L7,3 L0,6 z" fill="#f7768e"/>
    </marker>
  </defs>

  <!-- fondo -->
  <rect width="1280" height="360" fill="url(#bg)"/>

  <!-- texto -->
  <g transform="translate(64,112)">
    <text class="title">pipex</text>
    <text class="tag" y="48">Pipes · Redirections · Heredoc · PATH resolution</text>
    <text class="tag" y="78">C · dup2/execve · error handling</text>
  </g>

  <!-- composición derecha (máx. 520 px de ancho) -->
  <g transform="translate(720,60)">
    <!-- cajas de comandos (150px ancho, 40px separación) -->
    <g>
      <rect x="0"   y="40" width="150" height="60" rx="10" fill="#0b1020" stroke="#70a5fd" stroke-opacity=".6"/>
      <rect x="190" y="40" width="150" height="60" rx="10" fill="#0b1020" stroke="#70a5fd" stroke-opacity=".6"/>
      <rect x="380" y="40" width="150" height="60" rx="10" fill="#0b1020" stroke="#70a5fd" stroke-opacity=".6"/>
      <text class="mono" x="16"  y="78">cmd1</text>
      <text class="mono" x="206" y="78">cmd2</text>
      <text class="mono" x="396" y="78">outfile</text>
    </g>

    <!-- tuberías -->
    <path d="M150,70 C165,70 175,70 190,70" class="tube"/>
    <path d="M340,70 C355,70 365,70 380,70" class="tube"/>

    <!-- flechas -->
    <line x1="150" y1="70" x2="188" y2="70" stroke="#f7768e" stroke-width="2.5" marker-end="url(#arr)"/>
    <line x1="340" y1="70" x2="378" y2="70" stroke="#f7768e" stroke-width="2.5" marker-end="url(#arr)"/>

    <!-- línea de comando normal -->
    <g transform="translate(0,150)">
      <rect x="0" y="0" width="530" height="50" rx="10" fill="#0b1020" stroke="#bb9af7" stroke-opacity=".5"/>
      <text class="mono" x="12" y="32">./pipex infile "cmd1" "cmd2" outfile</text>
    </g>

    <!-- variante heredoc -->
    <g transform="translate(0,210)">
      <rect x="0" y="0" width="530" height="50" rx="10" fill="#0b1020" stroke="#7aa2f7" stroke-opacity=".5"/>
      <text class="mono" x="12" y="32">./pipex here_doc LIMITER "cmd1" "cmd2" outfile</text>
    </g>
  </g>
</svg>
