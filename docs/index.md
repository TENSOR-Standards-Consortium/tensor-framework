---
layout: default
title: Home
---

<!-- HERO -->
<section class="bg-gradient-to-r from-navy to-teal text-white py-20">
  <div class="max-w-4xl mx-auto text-center px-4">
    <img src="{{ site.baseurl }}/assets/images/logo-framework.png" alt="TENSOR Framework" class="mx-auto mb-8 h-48 w-auto"/>
    <h1 class="text-4xl font-extrabold mb-4">
      Unlock Consistent, Reproducible SOC Investigations
    </h1>
    <p class="text-lg mb-8">
      The TENSOR framework standardizes your SOC workflows into a single, versioned JSON graph—ready for human analysts and AI agents alike.
    </p>
    <a href="{{ site.baseurl }}/visualizer/" class="inline-block bg-white text-navy font-semibold py-3 px-6 rounded-lg shadow hover:bg-gray-100 transition">
      Launch Visualizer →
    </a>
  </div>
</section>

<!-- WHAT IS TENSOR -->
<section class="bg-gray-50 py-16">
  <div class="max-w-3xl mx-auto px-4">
    <h2 class="text-3xl font-bold mb-4">What Is TENSOR?</h2>
    <p class="text-lg text-gray-700 mb-6">
      TENSOR is a fully declarative JSON‑based decision graph, where each node
      represents a discrete investigative question (e.g., “Did the suspicious
      binary spawn child processes?”) and each directed edge encodes the
      conditional logic (“Yes”/“No” flows) guiding an analyst through a
      SOC‑grade triage. Nodes are tagged with one of seven primary categories—
      **File**, **Email**, **Host**, **Network**, **Identity**, **Cloud**,
      **Application**—and assigned a numerical weight reflecting their forensic
      priority. This structure captures the nonlinear reality of incident
      response—allowing back‑and‑forth loops between host and network indicators—
      while enforcing semantic versioning (`vX.Y.Z`) so a given playbook can be
      frozen in time for compliance audits, reproducibility, and regression testing.
    </p>
    <p class="text-lg text-gray-700">
      Under the hood, TENSOR maps cleanly to established frameworks: each question
      node can be annotated with MITRE ATT&CK tactic/technique IDs, and clusters
      of nodes align with NIST 800‑61r2’s IR phases—**Preparation**, **Detection**,
      **Containment**, **Eradication**, **Recovery**. Analysts and developers can
      import the JSON into any graph engine or Python/Go library to produce
      interactive UIs, run weighted‑node scoring for ML‑driven decision agents,
      or generate SOC‑playbook documentation. TENSOR is designed for seamless
      integration into SIEMs, SOAR platforms, and custom dashboards—providing a
      single source of truth for manual investigations, scripted pipelines, and
      future AI orchestration in high‑velocity environments.
    </p>
  </div>
</section>

<!-- WHY TENSOR CARDS -->
<section class="py-16">
  <div class="max-w-6xl mx-auto px-4 grid grid-cols-1 md:grid-cols-4 gap-8">
    <div class="bg-white rounded-lg shadow p-6 text-center">
      <img src="{{ site.baseurl }}/assets/icons/check.svg" alt="Check" class="mx-auto h-12 mb-4"/>
      <h3 class="font-semibold text-xl mb-2">Consistent Investigations</h3>
      <p>Everyone follows the same flow.</p>
    </div>
    <div class="bg-white rounded-lg shadow p-6 text-center">
      <img src="{{ site.baseurl }}/assets/icons/version.svg" alt="Version" class="mx-auto h-12 mb-4"/>
      <h3 class="font-semibold text-xl mb-2">Semantic Versioning</h3>
      <p>Lock to vX.Y.Z for audits.</p>
    </div>
    <div class="bg-white rounded-lg shadow p-6 text-center">
      <img src="{{ site.baseurl }}/assets/icons/plug.svg" alt="Plug" class="mx-auto h-12 mb-4"/>
      <h3 class="font-semibold text-xl mb-2">Extensible Modules</h3>
      <p>Plug in remediation or AI agents.</p>
    </div>
    <div class="bg-white rounded-lg shadow p-6 text-center">
      <img src="{{ site.baseurl }}/assets/icons/ai.svg" alt="AI" class="mx-auto h-12 mb-4"/>
      <h3 class="font-semibold text-xl mb-2">Tool‑Agnostic</h3>
      <p>Runs in any SIEM, SOAR, or custom UI.</p>
    </div>
  </div>
</section>

<!-- HOW TO GET STARTED -->
<section class="bg-gray-50 py-16">
  <div class="max-w-3xl mx-auto px-4">
    <h2 class="text-2xl font-bold mb-4">How To Get Started</h2>
    <ol class="list-decimal list-inside space-y-2 text-gray-700">
      <li>Download graph: <a href="{{ site.baseurl }}/core/latest/tensor-core.json" class="text-teal hover:underline">tensor-core.json</a></li>
      <li>Validate schema: <a href="{{ site.baseurl }}/schemas/tensor-schema.json" class="text-teal hover:underline">tensor-schema.json</a></li>
      <li>Explore visually: <a href="{{ site.baseurl }}/visualizer/" class="text-teal hover:underline">Launch Visualizer</a></li>
      <li>Contribute: propose questions or modules on GitHub.</li>
    </ol>
  </div>
</section>

<!-- DIVE DEEPER GRAPH PREVIEWS -->
<section class="py-16">
  <div class="max-w-4xl mx-auto px-4 text-center">
    <h2 class="text-2xl font-bold mb-6">Dive Deeper: See the Core Graph</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <img src="{{ site.baseurl }}/assets/images/graph-export1.png" alt="Graph export snapshot #1" class="h-64 w-auto object-contain rounded shadow-md mx-auto" />
      <img src="{{ site.baseurl }}/assets/images/graph-export2.png" alt="Graph export snapshot #2" class="h-64 w-auto object-contain rounded shadow-md mx-auto" />
    </div>
  </div>
</section>

<!-- GET INVOLVED CTA -->
<section class="bg-gray-800 text-white py-16">
  <div class="mt-10 flex justify-center space-x-6">
    <img src="{{ site.baseurl }}/assets/images/logo-consortium.png"
        alt="Consortium Logo"
        class="h-24 border-2 border-white p-2 rounded" />
  </div>
  <div class="max-w-3xl mx-auto px-4 text-center">
    <h2 class="text-3xl font-bold mb-4">Join the TENSOR Standards Consortium</h2>
    <p class="mb-6">Help us evolve the core investigative graph, build modules, or integrate TENSOR into your platform.</p>
    <a href="https://github.com/tensor-standards-consortium/tensor-framework"
       class="bg-teal text-navy font-semibold py-3 px-6 rounded-lg hover:bg-green-400 transition">
      View on GitHub
    </a>
  </div>
</section>
