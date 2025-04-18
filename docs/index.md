---
layout: default
title: Home
---

<div class="hero">
  <h1>Welcome to the TENSOR Framework</h1>
  <p>
    Threat Exploration & Non‑linear Security Orchestration & Response (TENSOR) 
    is an open, versioned standard for SOC investigative workflows. 
    Define your core decision‑tree once, plug in custom modules for remediation, 
    and power both human analysts and agentic AI.
  </p>
</div>

## Key Features

<div class="features">

  <div class="feature-card">
    <h3>Core Investigative Graph</h3>
    <p>
      A lightweight, JSON‑based decision‑flow of 70+ SOC questions 
      covering File, Email, Host, Network, User/Identity, Cloud & Application.
    </p>
  </div>

  <div class="feature-card">
    <h3>Semantic Versioning</h3>
    <p>
      Every release gets its own folder (e.g. v0.1.0). 
      Fetch `/core/latest/tensor-core.json` for the current graph  
      or lock to a specific version for reproducible investigations.
    </p>
  </div>

  <div class="feature-card">
    <h3>Interactive Visualizer</h3>
    <p>
      Built on Cytoscape.js—browse, filter, and explore nodes & edges 
      directly in your browser. Perfect for demos and analyst training.
    </p>
  </div>

  <div class="feature-card">
    <h3>Extension Modules</h3>
    <p>
      Keep the core investigation clean, then attach remediation 
      playbooks, business processes, or custom SOAR integrations 
      via separate module JSONs.
    </p>
  </div>

</div>

<div class="cta">
  <a href="{{ '/visualizer/' | relative_url }}">🚀 Launch Visualizer</a>
</div>

---

## Getting Started

1. **Download** the latest graph JSON:  
   [tensor-core.json →]({{ '/core/latest/tensor-core.json' | relative_url }})
2. **Read** the schema for structure:  
   [tensor-schema.json →]({{ '/schemas/tensor-schema.json' | relative_url }})
3. **Explore** with the visualizer:  
   [Open Visualizer →]({{ '/visualizer/' | relative_url }})
4. **Contribute** on GitHub:  
   - Propose new questions to `/core/vX.Y.Z/`  
   - Add remediation modules under `/modules/`

---

<footer>
<p>© {{ 'now' | date: "%Y" }} TENSOR Standards Consortium — Building the future of SOC investigations.</p>
</footer>
