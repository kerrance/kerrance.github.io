---
layout: default
title: Kerri Sharp's CV
description: This is my CV where you can find out more about my career and skills
og_description: This is my CV where you can find out more about my career and skills
keywords: Kerri Sharp CV, software engineer CV, web developer resume, work history, technical skills, developer portfolio, PHP developer, JavaScript developer, developer experience, UK software engineer, CV of Kerri Sharp
nav_title: CV
footer_type: cv
permalink: /cv/
---

<style>
  .headline {
    display: flex;
    justify-content: space-between;
  }

  @media only screen and (max-width: 1220px) {
    .headline {
      flex-direction: column;
    }
  }

  .position {
    display: inline-flex;
    flex-shrink: 1;
  }

  .dates {
    font-size: 1.6rem;
    font-weight: bold;
    display: inline-flex;
    flex-shrink: 0;
  }

  @media print {
    body {
      font-size: 10.5pt;
    }

    header {
      margin-bottom: 0;
    }

    section {
      margin-bottom: 10px;
    }

    .headline {
      border-bottom: solid 1px black;
      margin-bottom: 4px;
    }

    a:link {
      color: var(--color__black);
      text-decoration: none;
      text-underline-offset: initial;
      word-break: normal;
    }

    h1,
    h2 {
      text-decoration: none;
      text-underline-offset: initial;
    }

    h1 {
      font-size: 1.8em;
    }

    h2,
    .dates {
      font-size: 1.2em;
    }

    ul {
      padding-left: 15px;
    }

    li {
      margin-bottom: 0.2rem;
    }
  }
</style>

<header>
  <h1>Kerri Sharp</h1>

  <p>
    <a href="mailto:hello@kerrisharp.com">hello@kerrisharp.com</a>
  </p>
</header>

<main>
  <section>
    <p>
      Experienced software engineer and web developer specialising in bespoke web applications, websites, emails
      & APIs. Adept at delivering user-focused, testable solutions and passionate about fostering a healthy
      workplace culture. Industry experience in crafting impactful digital products and services since 2016.
    </p>

    <p>
      Key skills include React, Next.js, Vue.js, TypeScript, JavaScript, Tailwind, SASS, CSS, HTML, MJML, PHP,
      Laravel, WordPress, Go, MySQL, PostgreSQL, Docker, AWS, Supabase, Markdown, Agile, Scrum, Git, CI/CD, Jira
      & Figma.
    </p>
  </section>

  <section>
    <header class="headline">
      <h2 class="position">Software Engineer II, Intelligence Fusion / Sigma7</h2>

      <span class="dates">Sep 2021 – Apr 2025</span>
    </header>

    <ul>
      <li>
        Crafted a next-generation frontend with Next.js, TypeScript, Tailwind & Storybook as part of a Scrum
        team, deployed with Vercel. This greenfield SaaS empowered the company to package risk & intelligence
        services in a unique way to a plethora of new customers.
      </li>

      <li>
        Created a "Service Status" page as part of a team, interpreting uptime statistics from AWS CloudWatch,
        deployed as an AWS Lambda, written in Go 1.20 with a frontend written in React, TypeScript & Tailwind.
        This tool enabled customer to always know the status of the service, reducing support tickets and customer
        confusion.
      </li>

      <li>
        Led a team as project manager to build a "Spotify Wrapped"-alike using React, Vite, TypeScript, CSS &
        deployed with Netlify. Using internal APIs, we annually summarised the efforts of our intelligence analysts
        with a humorous presentation, improving team morale & encouraging competition.
      </li>

      <li>
        Contributed to building an AI virtual assistant platform leveraging Go 1.20 & AWS Bedrock, integrating
        Claude 3.5 to deliver context-rich customer interactions.
      </li>

      <li>
        Created a fully-documented REST API using PHP 8 (Slim), PostgreSQL & deployed via AWS to enable
        customers to share user generated content with their colleagues within the company's applications.
      </li>

      <li>
        Helped create an AWS Lambda written in Go 1.20, which continuously processes & sends notifications from
        AWS SQS payloads, offering enhanced user customisation of notifications and savings on third-party service
        costs.
      </li>

      <li>
        Built multi-factor authentication and authentication logging with PHP 8 (Slim) into the internal
        "Authentication" REST API, improving application security & enabling the acquisition of customers with
        enhanced security needs.
      </li>

      <li class="screen-only">
        Implemented the third-party "Dragonfly" API to display their data alongside internally published
        intelligence using PHP 8 (Lumen) to provide customers with more sources.
      </li>

      <li class="screen-only">
        Built a "Developer" website in Jekyll (Markdown, Liquid, SASS, JS) to document the company's APIs, resulting
        in increased sales from API-only customers.
      </li>

      <li class="screen-only">
        Delved into CQRS to update a legacy, event-driven, PHP API (Lumen), allowing intelligence analysts to keep
        information and statistics up-to-date via the event stream.
      </li>

      <li class="screen-only">
        Enhanced incident email notifications by dynamically generating map images using PHP 8 (Slim), MapTiler API,
        MJML & CSS, improving client awareness of threats or dangers occurring in their locations of interest.
      </li>
    </ul>
  </section>

  <section>
    <header class="headline">
      <h2 class="position">Web Developer, Think Productive</h2>

      <span class="dates">Dec 2020 – Aug 2021</span>
    </header>

    <ul>
      <li>
        Created a WordPress theme using PHP, SASS & JS (ES6, jQuery) as a central part of the company's global
        rebrand. By writing bespoke features, I reduced the reliance on third-party WordPress plugins from 63 down
        to 4. This vastly improved page load time and reduced employee frustration by making the website simpler to
        manage.
      </li>

      <li>
        Built a WordPress plugin using PHP 7.4, JS (jQuery) & CSS to create an asynchronous learning platform,
        empowering thousands of delegates globally to access workshop materials on-demand in multiple languages. My
        work replaced an expensive, third-party solution, prone to frequent outages.
      </li>

      <li>
        Converted a WordPress "multisite" into several, smaller databases with MySQL, giving all global branches the
        flexibility to manage, localise & translate their own websites to meet their regional marketing and sales
        goals.
      </li>
    </ul>
  </section>

  <section>
    <header class="headline">
      <h2 class="position">Web Developer, Opia</h2>

      <span class="dates">Jun 2016 – Nov 2020</span>
    </header>

    <ul>
      <li>
        Developed hundreds of sales promotion websites for clients including Google, Dell & HP using PHP 7.4
        (Laravel, Symfony, Blade), Vue.js, SASS (Bootstrap) & MySQL, deployed via DigitalOcean with Docker &
        Jenkins. These campaigns rewarded customers with cashback and gifts, incentivising tens of thousands of
        purchases, helping Opia's clients to meet their sales targets and strengthen brand loyalty.
      </li>

      <li>
        Led email campaign development, creating responsive HTML emails (MJML, Foundation for Email), tested with
        Litmus and delivered via Mailgun on behalf of clients including Samsung, Microsoft & LG. My work
        increased trust by reinforcing brand identity across digital communications and garnered positive client
        & customer feedback.
      </li>

      <li class="screen-only">
        Created a serial number validation system with PHP regex pattern matching to pre-validate customer claims.
        This reduced the amount of exploratory work required by the customer service team, minimising customer
        frustration.
      </li>

      <li>
        Represented the company at industry events by delivering presentations promoting best practices in
        responsive HTML email development. This helped establish Opia as a forward-thinking, tech-first employer and
        increased the number of job applications received from developers.
      </li>
    </ul>
  </section>
</main>
