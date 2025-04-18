---
layout: default
title: Home
---

<div class="hero">
  <h1>Why TENSOR?</h1>
  <p>
    Modern SOC teams drown in alerts and inconsistent processes. 
    TENSOR (Threat Exploration & Non‑linear Security Orchestration & Response)
    brings you:
  </p>
  <ul style="list-style: none; padding: 0; margin-top: 1.5rem;">
    <li>✔️ **Unified Investigations**: One core JSON graph—everyone follows the same steps.</li>
    <li>✔️ **Versioned & Auditable**: Lock your playbooks to vX.Y.Z so investigations are reproducible.</li>
    <li>✔️ **Plug‑and‑Play**: Attach remediation modules, automated playbooks, or AI‑agents.</li>
    <li>✔️ **Tool‑Agnostic**: Render it in any SIEM, SOAR or custom dashboard.</li>
  </ul>
</div>

## Dive Deeper

<div class="features">

  <div class="feature-card">
    <h3>Core Graph</h3>
    <p>
      75+ SOC questions spanning File, Email, Host, Network, Identity, Cloud & App.
      Define decision‑trees once; execute anywhere.
    </p>
  </div>

  <div class="feature-card">
    <h3>Graph JSON</h3>
    <p>
      Download any release:
      [Latest →]({{ '/core/latest/tensor-core.json' | relative_url }})
    </p>
    <p>
      Or pick a version from the dropdown above.
    </p>
  </div>

  <div class="feature-card">
    <h3>Schema</h3>
    <p>
      Strict JSON Schema ensures every release is valid:
      [View →]({{ '/schemas/tensor-schema.json' | relative_url }})
    </p>
  </div>

  <div class="feature-card">
    <h3>Visualizer</h3>
    <p>
      Browser‑based Cytoscape.js app—filter by category, weight, export
      snapshots, and train your team interactively.
    </p>
    <p>
      [Launch →]({{ '/visualizer/' | relative_url }})
    </p>
  </div>

</div>

<div class="cta">
  <a href="{{ '/visualizer/' | relative_url }}">🚀 Try the Visualizer</a>
</div>

---

## Get Involved

1. **Clone** the repo  
2. **Propose** new questions under `/core/vX.Y.Z/`  
3. **Build** your own modules under `/modules/`  
4. **Join** the TENSOR Standards Consortium on GitHub  

Let’s build consistent, reproducible SOC investigations—together. 🚀
