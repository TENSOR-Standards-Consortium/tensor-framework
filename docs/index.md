---
layout: default
title: Home
---

<div class="hero">
  <h1>Welcome to the TENSOR Framework</h1>
  <p>
    Threat Exploration & Non‑linear Security Orchestration & Response (TENSOR)
    is an open, versioned standard for Security Operations Center (SOC)
    investigative workflows.
  </p>
</div>

## Why TENSOR?

Modern SOC teams face alert fatigue, siloed tooling, and inconsistent
investigations. TENSOR provides:

- **Consistency & Transparency**  
  A single decision‑graph JSON everybody uses, so investigations follow the
  same steps every time.

- **Version Control & Reproducibility**  
  Semantic versions (e.g. v0.1.0, v1.0.0) let you lock in a point‑in‑time
  investigation for audits or training.

- **Extensibility**  
  Keep your core investigation clean, then bolt on remediation playbooks,
  ticketing workflows, or AI‑agent modules via separate JSON modules.

- **Tool‑Agnostic**  
  Works with any SIEM, SOAR, or custom dashboard—just fetch the JSON and
  render or execute your workflow.

<div class="cta">
  <a href="{{ '/visualizer/' | relative_url }}">🚀 Launch Interactive Visualizer</a>
</div>

---

## Key Features

<div class="features">

  <div class="feature-card">
    <h3>Core Investigative Graph</h3>
    <p>
      70+ curated SOC questions across File, Email, Host, Network,
      User/Identity, Cloud & Application categories.
    </p>
  </div>

  <div class="feature-card">
    <h3>Dynamic Version Selector</h3>
    <p>
      Switch between releases in your browser. Use the dropdown above
      to download a specific graph version or load it into the visualizer.
    </p>
  </div>

  <div class="feature-card">
    <h3>Schema‑Driven</h3>
    <p>
      JSON Schema (`/schemas/tensor-schema.json`) ensures every graph
      release adheres to the same structure.
    </p>
  </div>

  <div class="feature-card">
    <h3>Interactive Visualization</h3>
    <p>
      Cytoscape.js powers a rich browser UI—filter by category, weight,
      hover for details, and export your custom graph.
    </p>
  </div>

</div>

---

## Getting Started

1. **Download** the latest graph:  
   [tensor-core.json →]({{ '/core/latest/tensor-core.json' | relative_url }})
2. **Validate** against the schema:  
   [tensor-schema.json →]({{ '/schemas/tensor-schema.json' | relative_url }})
3. **Explore** with the visualizer:  
   [Launch →]({{ '/visualizer/' | relative_url }})
4. **Contribute** on GitHub:  
   - Add or revise questions under `/core/vX.Y.Z/`  
   - Create remediation or process modules under `/modules/`

