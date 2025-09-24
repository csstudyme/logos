<!-- techstack-logo.svg — professional, single-file SVG for README / SIH submission -->
<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="320" viewBox="0 0 1200 320" role="img" aria-label="Tech stack overview">
  <defs>
    <style>
      .bg { fill: #ffffff; }
      .card { fill: #0f172a; opacity: 0.04; rx: 18px; }
      .title { font: 700 28px/1 "Inter", Arial, sans-serif; fill: #0f172a; }
      .subtitle { font: 500 14px/1 "Inter", Arial, sans-serif; fill: #475569; }
      .section-label { font: 700 13px/1 "Inter", Arial, sans-serif; fill: #0f172a; }
      .tech { font: 600 13px/1 "Inter", Arial, sans-serif; fill: #0f172a; }
      .pill { fill: #ffffff; stroke: #e6eef6; stroke-width: 1; rx: 10px; }
      .divider { stroke: #e6eef6; stroke-width: 1; }
    </style>
  </defs>

  <rect width="1200" height="320" class="bg" />

  <!-- Left emblem -->
  <g transform="translate(28,28)">
    <rect width="220" height="264" rx="18" fill="#0ea5a4" />
    <text x="110" y="110" class="title" fill="#ffffff" text-anchor="middle">TECH</text>
    <text x="110" y="140" class="subtitle" fill="#ecfeff" text-anchor="middle">STACK OVERVIEW</text>
    <text x="110" y="172" class="subtitle" fill="#ecfeff" text-anchor="middle" style="font-weight:600;">(For SIH / Review)</text>
  </g>

  <!-- Right content card -->
  <g transform="translate(270,28)">
    <rect width="880" height="264" class="card" rx="16" />

    <!-- Header -->
    <text x="28" y="40" class="title">Tech stack — concise, production-ready</text>
    <text x="28" y="64" class="subtitle">Clear grouping for reviewers: Frontend · Backend · Blockchain · AI/Infra · APIs & DevOps</text>

    <!-- Divider -->
    <line x1="28" y1="78" x2="852" y2="78" class="divider" />

    <!-- Frontend -->
    <g transform="translate(28,92)">
      <rect x="0" y="0" width="820" height="40" class="pill" />
      <text x="12" y="26" class="section-label">Frontend</text>
      <text x="120" y="26" class="tech">React.js · React Native · Redux Toolkit · Tailwind CSS</text>
    </g>

    <!-- Backend -->
    <g transform="translate(28,142)">
      <rect x="0" y="0" width="820" height="40" class="pill" />
      <text x="12" y="26" class="section-label">Backend</text>
      <text x="120" y="26" class="tech">Node.js · Express.js · PostgreSQL · PostGIS · Redis · Socket.IO · RabbitMQ</text>
    </g>

    <!-- AI / Blockchain / Infra -->
    <g transform="translate(28,192)">
      <rect x="0" y="0" width="820" height="40" class="pill" />
      <text x="12" y="26" class="section-label">AI · Blockchain · Infra</text>
      <text x="210" y="26" class="tech">Python · PyTorch · Scikit-learn · TensorFlow Lite · ONNX · HuggingFace · Hyperledger Fabric · Solidity</text>
    </g>

    <!-- Bottom row: APIs & DevOps -->
    <g transform="translate(28,242)">
      <rect x="0" y="0" width="820" height="40" class="pill" />
      <text x="12" y="26" class="section-label">APIs & DevOps</text>
      <text x="160" y="26" class="tech">OpenStreetMap · Open-Meteo · Firebase Auth · Twilio · Cloudinary · AWS S3 · Docker · Docker Compose · GitHub Actions · Let's Encrypt · Prometheus · Grafana</text>
    </g>

  </g>

  <!-- Footer small note -->
  <text x="28" y="308" class="subtitle">Add to README: <tspan style="font-weight:700">![Tech Stack](./assets/techstack-logo.svg)</tspan></text>

</svg>
