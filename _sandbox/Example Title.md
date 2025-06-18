---
title: Example Title
permalink: /example-title/
variant: markdown
description: ""
---
  <style>
    :root {
      --primary: #1a1a1a;
      --accent: #d4af37;
      --light: #f8f8f8;
      --font: 'Helvetica Neue', sans-serif;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: var(--font);
      background-color: var(--light);
      color: var(--primary);
      line-height: 1.6;
    }

    header {
      background: center / contain no-repeat
				url("https://2924df7a-e523-46c3-b441-385a5a73d3fb.mdnpl…ev/shared-assets/images/examples/firefox-logo.svg"),
				#eee 35% url("https://2924df7a-e523-46c3-b441-385a5a73d3fb.mdnplay.dev/shared-assets/images/examples/lizard.png");
      color: white;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 0 1rem;
    }

    header h1 {
      font-size: 3rem;
      background-color: rgba(0, 0, 0, 0.6);
      padding: 1rem 2rem;
      border-radius: 10px;
    }

    section {
      padding: 3rem 1.5rem;
      max-width: 900px;
      margin: auto;
    }

    .highlight {
      color: var(--accent);
      font-weight: bold;
    }

    .info-box {
      background-color: white;
      padding: 2rem;
      border-left: 5px solid var(--accent);
      margin: 2rem 0;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    footer {
      background-color: #222;
      color: #aaa;
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
    }

    @media (min-width: 768px) {
      header h1 {
        font-size: 4rem;
      }

      .info-box {
        display: flex;
        gap: 2rem;
      }

      .info-box div {
        flex: 1;
      }
    }
  </style>

  <header>
    <h1>VISION '25<br>International Architecture Competition</h1>
  </header>

  <section>
    <h2>Overview</h2>
    <p>
      VISION '25 is a global design competition calling on architects, students, and designers to reimagine urban living in 2025. This year's theme is <span class="highlight">"Vertical Habitat"</span>—rethinking verticality in increasingly dense cities.
    </p>
  </section>

  <section class="info-box">
    <div>
      <h3>Important Dates</h3>
      <ul>
        <li><strong>Registration Opens:</strong> July 1, 2025</li>
        <li><strong>Submission Deadline:</strong> October 15, 2025</li>
        <li><strong>Winners Announced:</strong> December 1, 2025</li>
      </ul>
    </div>
    <div>
      <h3>Prizes</h3>
      <ul>
        <li>🏆 1st Prize: $5,000</li>
        <li>🥈 2nd Prize: $2,000</li>
        <li>🥉 3rd Prize: $1,000</li>
        <li>🖼 Honorable Mentions</li>
      </ul>
    </div>
  </section>

  <section>
    <h2>Submission Guidelines</h2>
    <p>
      Participants must submit a single A1 board in PDF format (portrait), clearly illustrating their concept. An abstract (max 300 words) and a unique project title must be included. Teams can consist of up to 3 members.
    </p>
  </section>

  <footer>
    © 2025 VISION Architecture Challenge. All rights reserved.<br>
    Contact us: info@vision25.org
  </footer>
