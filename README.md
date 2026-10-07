<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Lokesh Varma — Full-Stack Developer" />

<br/><br/>

<p align="center">
  <a href="https://my-portfolio-one-gold-42.vercel.app/"><img src="./assets/btn-portfolio.svg" height="40" alt="Portfolio" /></a>
  &nbsp;
  <!-- TODO: Insert public resume link -->
  <a href="https://my-portfolio-one-gold-42.vercel.app/"><img src="./assets/btn-resume.svg" height="40" alt="Resume (TODO)" /></a>
  &nbsp;
  <a href="mailto:lokeshvarmakshatriya@gmail.com"><img src="./assets/btn-email.svg" height="40" alt="Email" /></a>
  &nbsp;
  <a href="https://www.linkedin.com/in/natra-lokesh-493bb63a2/"><img src="./assets/btn-linkedin.svg" height="40" alt="LinkedIn" /></a>
  &nbsp;
  <a href="https://github.com/lokesh-varma28"><img src="./assets/btn-github.svg" height="40" alt="GitHub" /></a>
</p>

<br/>

<img src="./assets/stack-strip.svg" width="100%" alt="Core Engineering Stack Strip" />

</div>

<br/>

<img src="./assets/divider.svg" width="100%" alt="Section Divider" />

<br/>

<h2><img src="./assets/section-01-work.svg" alt="01 — SELECTED WORK" height="42" /></h2>

<!-- 2x2 Selected Work Grid -->
<table width="100%">
  <tr>
    <!-- Card 1: AI Chatbot Assistant -->
    <td width="50%" valign="top">
      <a href="https://ai-chatbot-f3t9.vercel.app">
        <!-- TODO: Replace placeholder with actual 1200x630 screenshot when available -->
        <img src="./assets/projects/ai-chatbot.svg" width="100%" alt="AI Chatbot Assistant Preview" />
      </a>
      <br/><br/>
      <b>AI Chatbot Assistant</b><br/>
      <sub>Contextual Google Gemini LLM assistant with multi-turn chat streaming and PDF document parsing.</sub>
      <br/><br/>
      <code>React 19</code> &nbsp; <code>Gemini API</code> &nbsp; <code>MongoDB</code>
      <br/><br/>
      <a href="https://ai-chatbot-f3t9.vercel.app"><b>Live Demo &rarr;</b></a> &nbsp;|&nbsp; <a href="https://github.com/lokesh-varma28/ai-chatbot"><b>Source Code &rarr;</b></a>
      <br/><br/>
      <details>
        <summary><b>Key architecture &amp; highlights</b></summary>
        <br/>
        • <b>Conversational AI Streaming:</b> Multi-turn conversational intelligence powered by the <b>Google Gemini API</b> (<code>@google/genai</code>) with prompt grounding.<br/>
        • <b>Document Intelligence:</b> Ingestion and text parsing of uploaded PDF files via <code>pdf-parse</code> and <code>multer</code> for document-grounded context Q&amp;A.<br/>
        • <b>Authenticated Sessions:</b> User authentication powered by <b>JWT</b> and <code>bcryptjs</code> password hashing with conversation threads in <b>MongoDB Atlas</b>.<br/>
        • <b>API Hardening:</b> Route rate limiting configured with <code>express-rate-limit</code> and HTTP security headers enforced via <b>Helmet</b>.<br/>
        • <b>Modern Client Interface:</b> Built with <b>React 19</b>, <b>Vite</b>, <code>react-markdown</code>, and <code>remark-gfm</code> for formatted responses.<br/>
        <br/>
        <b>Stack:</b> React 19 • Vite • Node.js • Express.js • Google Gemini API • MongoDB Atlas • JWT • PDF-Parse • Helmet • Vercel • Render
      </details>
    </td>
    <!-- Card 2: MERN E-Commerce -->
    <td width="50%" valign="top">
      <a href="https://mern-full-stack-ecommerce.vercel.app">
        <!-- TODO: Replace placeholder with actual 1200x630 screenshot when available -->
        <img src="./assets/projects/mern-ecommerce.svg" width="100%" alt="MERN E-Commerce Platform Preview" />
      </a>
      <br/><br/>
      <b>MERN E-Commerce Platform</b><br/>
      <sub>Multi-tier commerce architecture with independent storefront, seller portal, and Razorpay checkout.</sub>
      <br/><br/>
      <code>React</code> &nbsp; <code>Node.js / Express</code> &nbsp; <code>MongoDB</code>
      <br/><br/>
      <a href="https://mern-full-stack-ecommerce.vercel.app"><b>Live Demo &rarr;</b></a> &nbsp;|&nbsp; <a href="https://github.com/lokesh-varma28/Mern-Full-Stack-Ecommerce"><b>Source Code &rarr;</b></a>
      <br/><br/>
      <details>
        <summary><b>Key architecture &amp; highlights</b></summary>
        <br/>
        • <b>Multi-Tier Architecture:</b> Separated customer storefront and merchant dashboard connected to a centralized <b>Express.js REST API</b>.<br/>
        • <b>Dual Authentication:</b> <b>JWT</b> token sessions alongside <b>Google OAuth</b> (<code>google-auth-library</code>) for secure user sessions.<br/>
        • <b>Commerce Operations:</b> Real-time cart calculations, order lifecycle management, and atomic inventory stock tracking in <b>MongoDB</b>.<br/>
        • <b>Payments &amp; Invoices:</b> Integrated <b>Razorpay</b> checkout, <b>Cloudinary</b> media pipelines, and automated PDF invoice generation with <b>PDFKit</b>.<br/>
        • <b>Production Resilience:</b> <b>Redis</b>-backed route rate limiting (<code>rate-limit-redis</code>) and <b>Helmet</b> security headers.<br/>
        <br/>
        <b>Stack:</b> MongoDB • Express.js • React • Node.js • Redis • Razorpay • Cloudinary • PDFKit • Google OAuth • Vercel • Render
      </details>
    </td>
  </tr>
  <tr>
    <!-- Card 3: ApexStore -->
    <td width="50%" valign="top">
      <a href="https://apexstore-frontend.vercel.app">
        <!-- TODO: Replace placeholder with actual 1200x630 screenshot when available -->
        <img src="./assets/projects/apexstore.svg" width="100%" alt="ApexStore Preview" />
      </a>
      <br/><br/>
      <b>ApexStore</b><br/>
      <sub>API-driven e-commerce platform pairing a TypeScript React frontend with a PostgreSQL Django REST API.</sub>
      <br/><br/>
      <code>TypeScript</code> &nbsp; <code>Django REST</code> &nbsp; <code>PostgreSQL</code>
      <br/><br/>
      <a href="https://apexstore-frontend.vercel.app"><b>Live Demo &rarr;</b></a> &nbsp;|&nbsp; <a href="https://github.com/lokesh-varma28/Full-Stack-DRF-React"><b>Source Code &rarr;</b></a>
      <br/><br/>
      <details>
        <summary><b>Key architecture &amp; highlights</b></summary>
        <br/>
        • <b>Relational Backend:</b> Structured <b>Django REST Framework</b> API on <b>PostgreSQL</b> modeling products, categories, orders, and addresses.<br/>
        • <b>Authentication Integrity:</b> Secure token authentication powered by <b>Django SimpleJWT</b> with token refresh workflows.<br/>
        • <b>Type-Safe Client:</b> Component-driven frontend engineered with <b>React</b>, <b>TypeScript</b>, and <b>Vite</b> for contract safety.<br/>
        • <b>Payments &amp; Media:</b> Integrated <b>Razorpay</b> checkout and <b>Cloudinary</b> media pipelines for product catalogs.<br/>
        <br/>
        <b>Stack:</b> React • TypeScript • Python • Django REST Framework • PostgreSQL • SimpleJWT • Razorpay • Cloudinary • Vercel • Render
      </details>
    </td>
    <!-- Card 4: DeskHub -->
    <td width="50%" valign="top">
      <a href="https://client-chi-six-93.vercel.app">
        <!-- TODO: Replace placeholder with actual 1200x630 screenshot when available -->
        <img src="./assets/projects/deskhub.svg" width="100%" alt="DeskHub Preview" />
      </a>
      <br/><br/>
      <b>DeskHub</b><br/>
      <sub>Full-stack helpdesk platform featuring server-side Role-Based Access Control and automated testing.</sub>
      <br/><br/>
      <code>React</code> &nbsp; <code>Express / Zod</code> &nbsp; <code>Jest / Supertest</code>
      <br/><br/>
      <a href="https://client-chi-six-93.vercel.app"><b>Live Demo &rarr;</b></a> &nbsp;|&nbsp; <a href="https://github.com/lokesh-varma28/ProStackHub_CustomerAgentSystem"><b>Source Code &rarr;</b></a>
      <br/><br/>
      <details>
        <summary><b>Key architecture &amp; highlights</b></summary>
        <br/>
        • <b>Role-Based Access Control:</b> Server-enforced RBAC separating Customer ticket creation from Support Agent resolution queues.<br/>
        • <b>End-to-End TypeScript:</b> Unified contracts across <b>React</b> and <b>Node.js</b>/<b>Express.js</b> with <b>Zod</b> payload validation.<br/>
        • <b>Automated Testing Suite:</b> Integration test suite written in <b>Jest</b> and <b>Supertest</b> against an in-memory <b>MongoDB</b> instance.<br/>
        • <b>Lifecycle Triage:</b> Real-time status tracking (<code>Open</code>, <code>In Progress</code>, <code>Resolved</code>) with responsive triage dashboards.<br/>
        <br/>
        <b>Stack:</b> React • TypeScript • Node.js • Express.js • MongoDB • Zod • Jest • Supertest • Vercel
      </details>
    </td>
  </tr>
</table>

<br/>

<!-- Client Work Card: Dilip Optics Grand -->
<table width="100%">
  <tr>
    <td>
      <b>Dilip Optics Grand</b> &nbsp;·&nbsp; <code>Client Solution</code><br/>
      <sub>Mobile-first retail catalog engineered for an optical showroom in Rajahmundry with sub-second rendering.</sub><br/><br/>
      <code>React 19</code> &nbsp; <code>Tailwind CSS 4</code> &nbsp; <code>Node.js / Sharp</code><br/><br/>
      <a href="https://dilip-opticals-website.vercel.app"><b>Live Website &rarr;</b></a> &nbsp;|&nbsp; <a href="https://github.com/lokesh-varma28/dilip-opticals-website"><b>Source Code &rarr;</b></a>
      <br/><br/>
      <details>
        <summary><b>Client solution highlights</b></summary>
        <br/>
        • <b>High-Speed Frontend:</b> Built with <b>React 19</b>, <b>Vite 8</b>, and <b>Tailwind CSS 4</b> for sub-second mobile rendering.<br/>
        • <b>Automated Image Pipeline:</b> <b>Node.js</b> and <b>Sharp</b> scripts converting raw eyewear photography to lightweight WebP formats.<br/>
        • <b>Commercial Conversion:</b> One-tap WhatsApp appointment and product inquiry workflows driving direct showroom foot traffic.<br/>
        • <b>Local Business SEO:</b> Structured JSON-LD schema markup configured for high search engine visibility in Rajahmundry.
      </details>
    </td>
  </tr>
</table>

<br/>

<img src="./assets/divider.svg" width="100%" alt="Section Divider" />

<br/>

<h2><img src="./assets/section-02-experience.svg" alt="02 — EXPERIENCE" height="42" /></h2>

<table width="100%">
  <tr>
    <td>
      <h3 style="margin-top:0;">💼 Full-Stack Developer Intern</h3>
      <b><a href="https://www.linkedin.com/in/natra-lokesh-493bb63a2/">Godavari Wave Technologies</a></b> &nbsp;•&nbsp; 📍 <b>Rajahmundry, Andhra Pradesh, India</b><br/>
      <sub>⏱️ <b>3 Months</b> &nbsp;•&nbsp; 🟢 <b>Currently Working</b></sub> <!-- TODO: Add exact start date (e.g. July 2026 - Present) -->
      <br/><br/>
      • <b>Frontend Architecture:</b> Developing modular, responsive client applications in <b>React</b> with clean component state and modern UI patterns.<br/>
      • <b>Backend &amp; REST APIs:</b> Engineering secure server-side routes and controllers using <b>Node.js</b> and <b>Express.js</b>, enforcing route validation and authorization.<br/>
      • <b>Databases &amp; Quality:</b> Implementing data modeling and queries with <b>MongoDB</b>, wiring client views to server state, and validating API contracts with <b>Postman</b>.
    </td>
  </tr>
</table>

<br/>

<img src="./assets/divider.svg" width="100%" alt="Section Divider" />

<br/>

<h2><img src="./assets/section-03-stack.svg" alt="03 — TECHNICAL STACK" height="42" /></h2>

<p align="center">
  <img src="./assets/stack.svg" width="100%" alt="Core Engineering Capabilities — Languages: JavaScript, TypeScript, Python, HTML5, CSS3; Frontend: React, Tailwind CSS, Redux, Zustand; Backend and Data: Node.js, Express.js, Django REST Framework, PostgreSQL, MongoDB, Supabase, Firebase; Cloud and Tools: Vercel, Netlify, Render, Railway, Cloudflare, Git, GitHub, VS Code, Postman, Bruno, Thunder Client; AI-assisted: Cursor, Kiro, Antigravity, Windsurf, Gemini API" />
</p>

<p>
  <b>Currently exploring:</b> <code>React Native</code> and <code>Playwright</code> &nbsp;<!-- TODO: confirm the tool name "TRIM" (Trae?) -->
</p>

<blockquote>
  I use AI coding tools to move faster and review everything I ship.
</blockquote>

<br/>

<img src="./assets/divider.svg" width="100%" alt="Section Divider" />

<br/>

<!-- Tier 3: Compact / Collapsible -->
<details>
  <summary><b>04 — More Projects, Education &amp; Background</b></summary>
  <br/>

  <h3>📦 Additional Projects</h3>
  <table width="100%">
    <tr>
      <td width="33%" valign="top">
        <b>ProStackHub CartCraft</b><br/>
        <sub>MERN E-Commerce with Stripe checkout, RBAC, and Cloudinary media pipelines.</sub><br/><br/>
        <a href="https://frontend-silk-two-32.vercel.app/"><b>Live Demo &rarr;</b></a> &nbsp;|&nbsp; <a href="https://github.com/lokesh-varma28/ProStackHub-CartCraft"><b>Source Code &rarr;</b></a>
      </td>
      <td width="33%" valign="top">
        <b>ShelfLife Library</b><br/>
        <sub>Personal reading and bookshelf tracker built with React, Node.js, Express, and MongoDB.</sub><br/><br/>
        <a href="https://pro-stack-hub-shelf-life-ten.vercel.app"><b>Live Demo &rarr;</b></a> &nbsp;|&nbsp; <a href="https://github.com/lokesh-varma28/ProStackHub_ShelfLife"><b>Source Code &rarr;</b></a>
      </td>
      <td width="33%" valign="top">
        <b>Expense Tracker</b><br/>
        <sub>Financial visualization and spending analytics dashboard built in React.</sub><br/><br/>
        <a href="https://expense-tracker-dashboard-beta.vercel.app"><b>Live Demo &rarr;</b></a> &nbsp;|&nbsp; <a href="https://github.com/lokesh-varma28/expense-tracker-dashboard"><b>Source Code &rarr;</b></a>
      </td>
    </tr>
  </table>

  <br/>

  <h3>🎓 Education &amp; Certifications</h3>
  <table width="100%">
    <tr>
      <td width="50%" valign="top">
        <b>Bachelor of Commerce (B.Com)</b><br/>
        <b>Andhra University</b> · <i>Online Degree Program</i><br/>
        <sub>Expected Graduation: <b>2029</b></sub><br/><br/>
        <sub>Combining business fundamentals, financial models, and commercial workflows with dedicated full-stack software engineering practice.</sub>
      </td>
      <td width="50%" valign="top">
        <b>AI Fluency for Builders</b> &nbsp;<!-- TODO: Add certificate credential link --><br/>
        <b>Anthropic Academy</b><br/>
        <sub>Foundations in Large Language Models, prompt engineering architectures, and agentic workflows.</sub>
        <br/><br/>
        <b>Cisco Networking Academy</b> &nbsp;<!-- TODO: Add certificate credential link --><br/>
        <b>Cisco</b> • <b>Cisco Packet Tracer / Networking</b><br/>
        <sub>Core networking fundamentals, IP subnetting, routing protocols, and client-server communication models.</sub>
      </td>
    </tr>
  </table>

  <br/>

  <h3>📊 Engineering Activity</h3>
  <img src="./assets/activity-strip.svg" width="100%" alt="Activity Summary Strip" />
  <br/><br/>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lokesh-varma28/lokesh-varma28/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/lokesh-varma28/lokesh-varma28/output/github-snake.svg" />
    <img src="https://raw.githubusercontent.com/lokesh-varma28/lokesh-varma28/output/github-snake-dark.svg" width="100%" height="110" alt="GitHub Contribution Snake" />
  </picture>

</details>

<br/>

<img src="./assets/divider.svg" width="100%" alt="Section Divider" />

<br/>

<div align="center">
  <p>
    <b>Always Building · Always Learning · Always Shipping</b><br/>
    <sub>Let's connect: <a href="mailto:lokeshvarmakshatriya@gmail.com">lokeshvarmakshatriya@gmail.com</a> &nbsp;•&nbsp; <a href="https://www.linkedin.com/in/natra-lokesh-493bb63a2/">LinkedIn</a> &nbsp;•&nbsp; <a href="https://github.com/lokesh-varma28">GitHub</a> &nbsp;•&nbsp; <a href="https://my-portfolio-one-gold-42.vercel.app/">Portfolio</a></sub>
  </p>
  <br/>
  <img src="./assets/footer-wave.svg" width="100%" alt="Footer Wave" />
</div>
