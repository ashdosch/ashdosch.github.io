---
layout: default
title: Opuses
---

<section class="page-header">
  <h1>Opuses and Innovations</h1>
  <p>
    Selected technical projects and conceptions focused on data engineering, data science, data analysis, automation, AI and operational software prototypes.
  </p>
</section>

---

<section class="project-detail" id="data-bridge-framework">
  <h2>Canonical Data Bridge | Malleable ETL Framework for Ecommerce and Beyond</h2>

  <p>
    An enterprise-grade, metadata-driven Python ETL framework engineered to parse, normalize, and upsert complex unstructured data structures from multi-sheet spreadsheet matrices into low-latency relational data lakes. By decoupling data cleaning engines from layout mapping definitions via isolated declarative schemas, the platform dynamically handles extreme raw formatting variability while guaranteeing full historical lineage and downstream data warehouse integrity.
  </p>

  <p>
    <img src="../assets/images/data-bridge-diagram.svg" alt="Data Bridge Framework Architecture Diagram" style="max-width: 100%; height: auto; border: 1px solid #cbd5e1; border-radius: 8px; margin: 15px 0;" />
  </p>

  <h3>Highlights</h3>

  <ul>
    <li><strong>Declarative Layout Mapping:</strong> Decouples source layout parameters into structured YAML mapping profiles, removing hard-coded ingestion debt from the extraction layer.</li>
    <li><strong>High-Memory Vector Normalization:</strong> Utilizes highly optimized Pandas routines for programmatic header deduplication, custom regex pattern matching, and automated column truncation.</li>
    <li><strong>Fault-Tolerant Row Coercion:</strong> Validates and casts numeric scales and currency fields on-the-fly, isolating row-level processing anomalies into structural trace catalogs rather than raising global pipeline faults.</li>
    <li><strong>Windows-Safe File Operations:</strong> Implements robust single-handle read structures combined with reliable copy-then-delete filesystem logic to prevent resource handle collisions during high-volume server scheduling.</li>
    <li><strong>Transactional Storage Ingestion:</strong> Interfaces directly with relational target architectures using pyodbc to execute canonical staging table upserts and maintain live performance logs.</li>
  </ul>

  <p>
    <a class="button primary" href="https://github.com/ashdosch/Data-Bridge-Framework">View Repository</a>
    <a class="button secondary" href="projects/data-bridge" style="margin-left: 10px;">View Project Details</a>
  </p>
</section>

---


<section class="project-detail" id="spectrum-management-prototype">
  <h2>Spectrum Management Prototype | Robust and Modern Frequency Coordination for Public Safety</h2>

  <p>
    A secure, dedicated Frequency Coordination and FCC Form 601 Processing Platform. Engineered specifically for certified frequency coordination enterprises, radio frequency (RF) engineers, and spectrum administrators, this application streamlines the ingestion, technical validation, and federal submission lifecycle for Part 90 Public Safety Land Mobile Radio (PLMR) spectrum assets.
  </p>

  <p>
    <img src="../assets/images/spec-mana-diagram.svg" alt="Spectrum Platform System Architecture Diagram" style="max-width: 100%; height: auto; border: 1px solid #cbd5e1; border-radius: 8px; margin: 15px 0;" />
  </p>

  <h3>Planned Features</h3>

  <ul>
    <li><strong>Gated Public Intake Portal:</strong> An identity-constrained submission dashboard built with clean web form components that validates guest eligibility based on official public safety domains before ingestion.</li>
    <li><strong>Syntactic Coordinate Checking:</strong> A backend geometric verification engine that validates longitude and latitude fields against strict CONUS bounding-box definitions prior to routing records to the internal queue.</li>
    <li><strong>Spatial Core Integration:</strong> Leverages a relational PostgreSQL storage tier combined with the PostGIS extension to handle low-latency spatial indexing, radial tower boundaries, and co-channel contour overlap analysis.</li>
    <li><strong>Form 601 Compliance Wizard:</strong> Replaces traditional filing overhead with a dynamic validation layout enforcing strict type checks for mandatory emission designators and public safety radio service codes (PW/YW).</li>
    <li><strong>Automated Lifecycle Tracking:</strong> Features a scheduled background cron architecture that monitors call sign lifecycle stages, triggers proactive expiration/renewal tracking flags, and serializes certified blocks into pipe-delimited federal exchange streams.</li>
  </ul>

  <p>
    <a class="button primary" href="https://github.com/ashdosch/Spectrum-Management-Prototype">View Repository</a>
    <a class="button secondary" href="projects/spectrum-management" style="margin-left: 10px;">View Core Platform docs</a>
    <a class="button secondary" href="projects/spectrum-management-dash-static" style="margin-left: 10px;">View Example Portal UI</a>
  </p>
</section>

---


<section class="project-detail" id="data-matching-toolkit">
  <h2>Data Scrubbing | Algorithms and Data Models for Rectifying Industry Agnostic Data</h2>

  <p>
    A modular programmatic series of scripts focused on cross-system entity resolution, alphanumeric record linkage, and string similarity normalization. Developed to address the problem of data fragmentation across siloed operational architectures, this set combines advanced deterministic cleansing rules with customizable fuzzy matching algorithms to isolate, deduplicate, and merge overlapping transaction logs, catalog entries, and reference registries without compromising processing velocity.
  </p>

  <p>
    <img src="../assets/images/data-scrubbing.gif" alt="Data Scrubbing In Action" style="max-width: 100%; height: auto; border: 1px solid #cbd5e1; border-radius: 8px; margin: 15px 0;" />
  </p>

  <h3>UNDER CONSTRUCTION</h3>

<!--
  <h3>Highlights</h3>

  <ul>
    <li><strong>Algorithmic Tokenization:</strong> Extracts and standardizes raw text segments using customized phonetic weights and string-distance metrics to process variant nomenclature natively.</li>
    <li><strong>Schema Reconciliation Pipelines:</strong> Implements configurable matching matrices to align disjointed source elements into strict canonical formats, fixing manual data transmission typos automatically.</li>
    <li><strong>Lineage Resolution Trace:</strong> Compiles an immutable history ledger recording raw field variance, structural confidence scores, and transformation links to preserve tracking continuity.</li>
    <li><strong>Transactional Volume Optimization:</strong> Utilizes vector block grouping parameters to drastically accelerate evaluation indexing over large-scale dataset arrays.</li>
  </ul>

  <p>
    <a class="button primary" href="https://github.com/ashdosch/Data-Scrubbing-Toolkit">View Repository</a>
  </p>

-->  
</section>