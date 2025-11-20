<p align="center">
  <img src="https://www.yourtransfer24.com/wp-content/uploads/2019/04/Logo-Your-Transfer-24_Web.png" width="180" alt="YourTransfer24 Logo">
</p>

<h1 align="center">YourTransfer24 — REST API Developer Platform</h1>

<p align="center">Official technical resources and SDK ecosystem for the YourTransfer24 JSON REST API.</p>

<p align="center">
  <img src="https://img.shields.io/badge/API_Version-v1.3.3-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-Private-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Access-By_Invitation_Only-blue?style=for-the-badge">
</p>

<hr/>

<h2>Platform Overview</h2>

<p>
YourTransfer24 provides a private, secure, enterprise-grade mobility API for OTAs, travel companies, booking engines, and integration partners. 
All API specifications, Swagger UI access, and environment controls are delivered exclusively through the private Developer Dashboard.
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

<h2>Repository Visibility & Distribution Policy</h2>

<p>
YourTransfer24 maintains a visibility strategy aligned with the requirements of each package registry. 
Only SDKs that require public visibility for installation remain public. The rest are kept private to protect internal infrastructure, logic, and proprietary systems.
</p>

<h3>Public SDK Repositories</h3>

<ul>
  <li>
    <strong>yt24-sdk-php</strong> — Public (required by Packagist)<br>
    <code>composer require yourtransfer24/yt24-sdk</code><br>
    <a href="https://github.com/YourTransfer24/yt24-sdk-php">https://github.com/YourTransfer24/yt24-sdk-php</a>
  </li>

  <li>
    <strong>yt24-sdk-java</strong> — Public (required by Maven Central)<br>
    <code>
&lt;dependency&gt;<br>
&nbsp;&nbsp;&lt;groupId&gt;com.yourtransfer24&lt;/groupId&gt;<br>
&nbsp;&nbsp;&lt;artifactId&gt;yt24-sdk&lt;/artifactId&gt;<br>
&nbsp;&nbsp;&lt;version&gt;1.3.3&lt;/version&gt;<br>
&lt;/dependency&gt;
    </code><br>
    <a href="https://github.com/YourTransfer24/yt24-sdk-java">https://github.com/YourTransfer24/yt24-sdk-java</a>
  </li>

  <li>
    <strong>.github</strong> — Public organization profile & documentation<br>
    <a href="https://github.com/YourTransfer24/.github">https://github.com/YourTransfer24/.github</a>
  </li>
</ul>

<h3>Private SDK Repositories</h3>

<p>
These repositories remain private because npm and PyPI do not require public GitHub repositories for global package installation.
</p>

<ul>
  <li><strong>yt24-api-examples</strong> — Endpoint workflows</li>
  <li><strong>yt24-sdk-js</strong> — JavaScript SDK</li>
  <li><strong>yt24-sdk-node</strong> — Node.js SDK</li>
  <li><strong>yt24-sdk-python</strong> — Python SDK</li>
  <li><strong>Centralized Example Repository</strong> — Booking lifecycle and typed flows</li>
</ul>

<p>
Private repositories include version control, authentication helpers, request and response models, booking lifecycle workflows, environment configuration, coverage utilities, and realistic JSON structures.
</p>

<hr/>

<h2>SDK Distribution Model</h2>

<pre>
JSON REST API (v1.3.3)
├── yt24-sdk-php        Public (required by Packagist)
├── yt24-sdk-js         Private (npm publication allowed)
├── yt24-sdk-node       Private (npm publication allowed)
├── yt24-sdk-java       Public (required by Maven Central)
└── yt24-sdk-python     Private (PyPI publication allowed)
</pre>

<p>
All SDKs include authentication flows, method references, booking lifecycle examples, schema validation, and typed JSON structures for reliable integration.
</p>

<hr/>

<h2>Official SDK Installation</h2>

<h3>Python (PyPI)</h3>
<pre>pip install yt24-sdk</pre>
<p>
<a href="https://pypi.org/project/yt24-sdk/">PyPI Package</a><br>
<a href="https://github.com/YourTransfer24/yt24-sdk-python">Python GitHub Repo</a>
</p>

<h3>JavaScript / Node (npm)</h3>
<pre>npm install yt24-sdk</pre>
<p>
<a href="https://www.npmjs.com/package/yt24-sdk">npm Package</a><br>
<a href="https://github.com/YourTransfer24/yt24-sdk-js">JavaScript GitHub Repo</a>
</p>

<h3>PHP (Packagist)</h3>
<pre>composer require yourtransfer24/yt24-sdk</pre>
<p>
<a href="https://packagist.org/packages/yourtransfer24/yt24-sdk">Packagist Package</a><br>
<a href="https://github.com/YourTransfer24/yt24-sdk-php">PHP GitHub Repo</a>
</p>

<h3>Java (Maven Central)</h3>
<pre>
&lt;dependency&gt;
  &lt;groupId&gt;com.yourtransfer24&lt;/groupId&gt;
  &lt;artifactId&gt;yt24-sdk&lt;/artifactId&gt;
  &lt;version&gt;1.3.3&lt;/version&gt;
&lt;/dependency&gt;
</pre>
<p>
<a href="https://central.sonatype.com/artifact/com.yourtransfer24/yt24-sdk">Maven Central</a><br>
<a href="https://github.com/YourTransfer24/yt24-sdk-java">Java GitHub Repo</a>
</p>

<hr/>

<h2>Developer Tools</h2>

<ul>
  <li>Private Swagger UI (sandbox and production)</li>
  <li>Developer Dashboard (API key and environment management)</li>
  <li>Environment isolation and strict versioning</li>
  <li>Structured onboarding workflow and technical guidance</li>
  <li>Centralized logging and activity endpoints</li>
</ul>

<hr/>

<h2>Support</h2>

<p>
For partnerships, integrations, or onboarding assistance:<br>
<strong>api.support@yourtransfer24.com</strong>
</p>

<p align="center" style="color:#7F8C8D; font-size:13px;">
© YourTransfer24 — REST API Platform and Developer Resources
</p>

