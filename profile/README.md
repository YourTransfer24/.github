<p align="center">
  <img src="https://www.yourtransfer24.com/wp-content/uploads/2019/04/Logo-Your-Transfer-24_Web.png" width="180" alt="YourTransfer24 Logo">
</p>

<h1 align="center">YourTransfer24 — REST API Developer Platform</h1>

<p align="center">
Official technical resources and SDK ecosystem for the YourTransfer24 JSON REST API.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/API_Version-v1.3.3-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-Private-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Access-By_Invitation_Only-blue?style=for-the-badge">
</p>

<hr/>

<h2>Platform Overview</h2>

<p>
YourTransfer24 provides a private, secure, enterprise-grade mobility API for OTAs, travel companies, booking engines, and integration partners. 
All API specifications, Swagger UI access, environment controls, and complete documentation are delivered exclusively through the private Developer Dashboard.
</p>

<ul>
  <li>Private Sandbox and Production environments</li>
  <li>Strict JSON schema definitions with versioned releases</li>
  <li>Private Swagger UI for endpoint exploration</li>
  <li>Developer Dashboard for API key lifecycle management</li>
  <li>Structured onboarding and integration workflow</li>
  <li>Enterprise authentication model</li>
</ul>

<hr/>

<h2>Repository Visibility and Distribution Policy</h2>

<p>
YourTransfer24 maintains a visibility strategy aligned with the requirements of each package registry and the need to protect backend logic, infrastructure, and proprietary systems.
</p>

<h3>Public Repositories</h3>

<p>
Only SDKs that require public visibility for installation via official package managers are published publicly. 
At this time, the PHP SDK is the only public SDK because Packagist requires a public repository.
</p>

<ul>
  <li>
    <a href="https://github.com/YourTransfer24/yt24-sdk-php"><strong>yt24-sdk-php</strong></a> — Public  
    <br>
    Global installation allowed using:  
    <code>composer require yourtransfer24/yt24-sdk-php</code>
  </li>
  <li>
    <a href="https://github.com/YourTransfer24/.github"><strong>.github</strong></a> — Public  
    Organization profile and public documentation.
  </li>
</ul>

<h3>Private Repositories</h3>

<p>
All other SDKs and integration resources remain private. npm, PyPI, and Maven do not require public GitHub repositories to publish packages, which allows these SDKs to remain private while still being distributed through their respective registries in the future.
</p>

<ul>
  <li><strong>yt24-api-examples</strong> — Full example flows and endpoint demonstrations</li>
  <li><strong>yt24-sdk-js</strong> — JavaScript SDK</li>
  <li><strong>yt24-sdk-node</strong> — Node.js SDK</li>
  <li><strong>yt24-sdk-java</strong> — Java SDK</li>
  <li><strong>yt24-sdk-python</strong> — Python SDK</li>
</ul>

<p>
These repositories include authentication utilities, booking flow helpers, typed request and response structures, environment configuration, availability and coverage wrappers, and full integration workflows.
</p>

<p>
No backend logic, infrastructure, or proprietary business rules are stored in public repositories.
</p>

<hr/>

<h2>SDK Distribution Model</h2>

<pre>
JSON REST API (v1.3.3)
├── yt24-sdk-php        Public (required by Packagist)
├── yt24-sdk-js         Private (npm publication allowed without public repo)
├── yt24-sdk-node       Private (npm publication allowed without public repo)
├── yt24-sdk-java       Private (Maven Central publication allowed)
└── yt24-sdk-python     Private (PyPI publication allowed)
</pre>

<p>
All SDKs include version control, authentication flows, booking lifecycle examples, method references, schema validation, and typed JSON structures for reliable integration.
</p>

<hr/>

<h2>Developer Tools</h2>

<ul>
  <li>Private Swagger UI for sandbox and production</li>
  <li>Developer Dashboard for API key management</li>
  <li>Environment-level isolation and versioning</li>
  <li>Structured onboarding and technical guidance</li>
  <li>Centralized logging and activity endpoints</li>
</ul>

<hr/>

<h2>Support</h2>

<p>
For partnership requests, SDK access, or onboarding assistance:  
<strong>api.support@yourtransfer24.com</strong>
</p>

<br/>

<p align="center" style="color:#7F8C8D; font-size:13px;">
© YourTransfer24 — REST API Platform and Developer Resources
</p>

