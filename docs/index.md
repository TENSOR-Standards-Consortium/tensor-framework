---
layout: default
title: Home
---

<!-- Why TENSOR? as a separate section -->
<section class="section dark">
  <div class="container three-col">
    <div>
      <h2>What Is TENSOR?</h2>
      <p>
        A JSON‑first, tool‑agnostic standard detailing 75+ SOC investigative
        questions across File, Email, Host, Network, Identity, Cloud & Application.
      </p>
    </div>
    <div>
      <h2>Why TENSOR?</h2>
      <ul>
        <li>✅ <strong>Consistent Investigations</strong>—every analyst follows the same flow.</li>
        <li>✅ <strong>Semantic Versioning</strong>—lock to vX.Y.Z for audits and training.</li>
        <li>✅ <strong>Extensible Modules</strong>—attach playbooks, SOAR apps, or AI agents.</li>
        <li>✅ <strong>Tool‑Agnostic</strong>—works with any SIEM or custom dashboard.</li>
      </ul>
    </div>
    <div>
      <h2>How To Get Started</h2>
      <ol>
        <li>
          <strong>Download graph:</strong>
          <a href="{{ '/core/latest/tensor-core.json' | relative_url }}">tensor-core.json</a>
        </li>
        <li>
          <strong>Validate schema:</strong>
          <a href="{{ '/schemas/tensor-schema.json' | relative_url }}">tensor-schema.json</a>
        </li>
        <li>
          <strong>Explore visually:</strong>
          <a href="{{ '/visualizer/' | relative_url }}">Launch Visualizer</a>
        </li>
        <li>
          <strong>Contribute:</strong> propose questions or modules on GitHub.
        </li>
      </ol>
    </div>
  </div>
</section>

<!-- Dive Deeper with icon cards -->
<section class="section light">
  <div class="container features">
    <div class="card">
      <img src="{{ '/assets/icons/graph.svg'   | relative_url }}" class="card-icon" alt="">
      <h3>Core Investigative Graph</h3>
      <p>Detailed decision‑trees for every suspicious event, in an open JSON format.</p>
    </div>
    <div class="card">
      <img src="{{ '/assets/icons/version.svg' | relative_url }}" class="card-icon" alt="">
      <h3>Version Control</h3>
      <p>Lock your investigations to vX.Y.Z for reproducibility and compliance.</p>
    </div>
    <div class="card">
      <img src="{{ '/assets/icons/plug.svg'    | relative_url }}" class="card-icon" alt="">
      <h3>Extensible Modules</h3>
      <p>Attach remediation playbooks or automated actions without touching core.</p>
    </div>
    <div class="card">
      <img src="{{ '/assets/icons/ai.svg'      | relative_url }}" class="card-icon" alt="">
      <h3>AI & Automation</h3>
      <p>Power AI‑agent workflows with the exact same graph you use manually.</p>
    </div>
  </div>
</section>

<!-- Get Involved call to action -->
<section class="section dark get-involved">
  <div class="container">
    <h2>Join the TENSOR Standards Consortium</h2>
    <p>
      Help us evolve the core investigative graph, build remediation modules,
      or integrate TENSOR into your tools.
    </p>
    <a class="button" href="https://github.com/tensor-standards-consortium/tensor-framework">
      View on GitHub
    </a>
  </div>
</section>
