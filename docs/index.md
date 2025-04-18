---
layout: default
title: Home
---

<!-- Why TENSOR Section -->
<section class="section dark">
  <div class="container three-col">
    <div>
      <h2>What Is TENSOR?</h2>
      <p>A JSON‑first standard defining 75+ investigative questions across File, Email,
         Host, Network, Identity, Cloud & Application domains.</p>
    </div>
    <div>
      <h2>Why TENSOR?</h2>
      <ul>
        <li>✅ <strong>Consistent Investigations</strong>—everyone follows the same flow.</li>
        <li>✅ <strong>Semantic Versioning</strong>—lock to vX.Y.Z for audits.</li>
        <li>✅ <strong>Extensible Modules</strong>—plug in remediation or AI agents.</li>
        <li>✅ <strong>Tool‑Agnostic</strong>—runs in any SIEM, SOAR, or custom UI.</li>
      </ul>
    </div>
    <div>
      <h2>How To Get Started</h2>
      <ol>
        <li>Download graph: 
          <a href="{{ '/core/latest/tensor-core.json' | relative_url }}">tensor-core.json</a>
        </li>
        <li>Validate schema: 
          <a href="{{ '/schemas/tensor-schema.json' | relative_url }}">tensor-schema.json</a>
        </li>
        <li>Explore visually:
          <a href="{{ '/visualizer/' | relative_url }}">Launch Visualizer</a>
        </li>
        <li>Contribute: propose questions or modules on GitHub.</li>
      </ol>
    </div>
  </div>
</section>

<!-- Dive Deeper Graph Previews -->
<section class="section light">
  <div class="container">
    <h2 style="text-align:center; margin-bottom:2rem;">Dive Deeper: See the Core Graph</h2>
    <div class="graph-previews">
      <!-- Place your two exports here -->
      <img src="{{ '/assets/images/graph-export1.png' | relative_url }}"
           alt="Graph export snapshot #1" />
      <img src="{{ '/assets/images/graph-export2.png' | relative_url }}"
           alt="Graph export snapshot #2" />
    </div>
  </div>
</section>

<!-- Get Involved -->
<section class="section dark get-involved">
  <h2>Join the TENSOR Standards Consortium</h2>
  <p>Help us evolve the core investigative graph, build modules,
     or integrate TENSOR into your platform.</p>
  <a class="button" href="https://github.com/tensor-standards-consortium/tensor-framework">
    View on GitHub
  </a>
</section>
