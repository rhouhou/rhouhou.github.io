---
layout: default
title: Research
---

<section class="card">
  <h1>Research</h1>

  <p>
    My research focuses on AI-driven computational modeling for biophotonics, spectroscopy, medical imaging, and scientific measurement systems under uncertainty.
  </p>

  <p>
    I work on methods that combine physics-informed modeling, inverse problems, simulation, validation, and data-efficient machine learning for scientific domains where measurements are noisy, limited, multimodal, or difficult to interpret.
  </p>

  <hr>

  <h3>Research Vision</h3>

  <p>
    Modern scientific measurement systems often produce data that are incomplete, noisy, indirect, or affected by instrument and sample variability.
  </p>

  <p>
    My goal is to develop computational methods that are physically meaningful, interpretable, uncertainty-aware, robust under domain shift, and suitable for real scientific workflows.
  </p>

  <p>
    Rather than treating scientific AI as black-box prediction, I focus on models and workflows that respect measurement physics, prior knowledge, and validation requirements.
  </p>

  <hr>

  <h3>Research Areas</h3>

  <h4>AI for Biophotonics and Spectroscopy</h4>

  <p>
    I am interested in AI methods for optical and spectroscopic measurement systems, especially Raman, CARS, BCARS, and related biophotonic modalities.
  </p>

  <ul class="compact-list">
    <li><strong>Simulation</strong> <span class="where">- realistic spectra under instrument, noise, calibration, and biochemical variability</span></li>
    <li><strong>Retrieval</strong> <span class="where">- phase retrieval, non-resonant-background correction, and Raman-like signal recovery</span></li>
    <li><strong>Validation</strong> <span class="where">- artifact detection, physical plausibility checks, and Raman consistency scoring</span></li>
    <li><strong>Benchmarking</strong> <span class="where">- domain-shift-aware evaluation for scientific AI workflows</span></li>
  </ul>

  <h4>Scientific Machine Learning Under Data Scarcity</h4>

  <p>
    Many scientific and medical domains have limited labeled data, expensive measurements, heterogeneous acquisition conditions, or strong domain shift.
  </p>

  <ul class="compact-list">
    <li><strong>Data-efficient learning</strong> <span class="where">- building useful models when labeled data are limited</span></li>
    <li><strong>Simulation-driven learning</strong> <span class="where">- using controlled synthetic data to test robustness and generalization</span></li>
    <li><strong>Uncertainty-aware evaluation</strong> <span class="where">- measuring reliability beyond accuracy alone</span></li>
    <li><strong>Reproducible benchmarks</strong> <span class="where">- designing transparent evaluation workflows for scientific AI</span></li>
  </ul>

  <h4>Medical Imaging and Multimodal Data</h4>

  <p>
    I also work on medical imaging and biomedical AI workflows involving classification, reconstruction quality, and model evaluation.
  </p>

  <ul class="compact-list">
    <li><strong>Medical image classification</strong> <span class="where">- model evaluation under limited data and uncertainty</span></li>
    <li><strong>Reconstruction quality</strong> <span class="where">- understanding how artifacts and reconstruction errors affect downstream analysis</span></li>
    <li><strong>Multimodal imaging</strong> <span class="where">- connecting imaging, spectroscopy, and structured scientific information</span></li>
    <li><strong>Trustworthy AI</strong> <span class="where">- calibration, uncertainty, validation, and responsible interpretation</span></li>
  </ul>

  <h4>Inverse Problems and Reconstruction</h4>

  <p>
    My mathematical background is in inverse problems, PDE-constrained modeling, probability, statistics, and scientific computation.
  </p>

  <ul class="compact-list">
    <li><strong>Ill-posed inverse problems</strong> <span class="where">- stability, regularization, and identifiability</span></li>
    <li><strong>Physics-informed reconstruction</strong> <span class="where">- using measurement models and constraints to guide inference</span></li>
    <li><strong>Model mismatch</strong> <span class="where">- understanding uncertainty when assumptions are imperfect</span></li>
    <li><strong>Inverse operator learning</strong> <span class="where">- combining mathematical structure with machine learning</span></li>
  </ul>

  <hr>

  <h3>Current Project Ecosystem</h3>

  <h4>CARSBench</h4>

  <p>
    CARSBench is a variability-aware simulation and benchmark framework for cross-domain generalization in CARS/BCARS reconstruction.
  </p>

  <p>
    It is designed to generate spectra under controlled domain shifts and evaluate how retrieval or learning workflows generalize across acquisition and biochemical variability.
  </p>

  <p>
    <a href="https://github.com/rhouhou/CARSBench">GitHub repository</a>
  </p>

  <h4>prCARS</h4>

  <p>
    prCARS is a Python toolkit for phase retrieval, non-resonant-background correction, preprocessing, and Raman-like signal reconstruction from CARS/BCARS spectra.
  </p>

  <p>
    It acts as the retrieval layer between simulated or measured coherent Raman spectra and Raman-like downstream analysis.
  </p>

  <p>
    <a href="https://github.com/rhouhou/prCARS">GitHub repository</a>
  </p>

  <h4>CARSGuard</h4>

  <p>
    CARSGuard is a validation and quality-control framework for assessing physical realism, Raman consistency, artifact risk, and confidence in CARS/BCARS spectra.
  </p>

  <p>
    It is designed to flag suspicious spectra, support validation reports, and make spectroscopy workflows more interpretable.
  </p>

  <p>
    <a href="https://github.com/rhouhou/CARSGuard">GitHub repository</a>
  </p>

  <p style="margin-top: 1rem; color: var(--muted);">
    Together, these projects form a small research ecosystem for simulation, retrieval, and validation of coherent Raman spectroscopy workflows.
  </p>

  <hr>

  <h3>Methods</h3>

  <ul class="compact-list">
    <li><strong>Physics-informed machine learning</strong> <span class="where">- combining data-driven methods with scientific constraints</span></li>
    <li><strong>Inverse problem theory</strong> <span class="where">- modeling indirect measurements and unstable reconstructions</span></li>
    <li><strong>Spectral signal processing</strong> <span class="where">- preprocessing, retrieval, background correction, and feature extraction</span></li>
    <li><strong>Simulation and synthetic data</strong> <span class="where">- generating controlled benchmark data for scientific AI</span></li>
    <li><strong>Validation metrics</strong> <span class="where">- evaluating plausibility, consistency, artifacts, and confidence</span></li>
    <li><strong>Reproducible scientific Python</strong> <span class="where">- building tested and documented research software</span></li>
  </ul>

  <hr>

  <h3>Long-Term Direction</h3>

  <p>
    My long-term research direction is to develop reliable AI workflows for scientific measurement systems, especially in biophotonics, spectroscopy, and medical imaging.
  </p>

  <p>
    I am especially interested in research and engineering roles where mathematical modeling, scientific AI, biomedical measurement systems, and trustworthy validation meet.
  </p>
</section>
