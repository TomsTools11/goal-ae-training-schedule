# GOAL — Account Executive Training Schedule

A static single-page site that presents the 2-week new-hire training schedule for GOAL Account Executives. Built with vanilla HTML, CSS, and JavaScript and deployed on Netlify.

## Overview

This site serves as the onboarding reference for new GOAL AEs, covering 8 training days and 16 sessions across two weeks:

- **Week 1 — Foundation:** Internal tools setup (Notion, Claude Cowork, Close CRM), product deep dive, competitive intelligence, discovery methodology, and demo/close techniques.
- - **Week 2 — Depth:** TCPA compliance and 1-to-1 consent, advanced sales positioning, consultative campaign targeting, and a full-cycle certification capstone.
 
  - ## Features
 
  - - Dark-themed, responsive design using the Red Hat Display and Inter typefaces
    - - Accordion day cards that expand to show session details, topics, and daily activities
      - - Filter bar to view sessions by week or category (Software, Sales)
        - - Color-coded category tags and legend (Software & Tools, Sales Skills, Practice / Application)
          - - Print-friendly stylesheet
          - Security headers configured via `netlify.toml`
         
          - ## Project Structure
         
          - ```
            ├── index.html          # Single-page application (HTML + embedded CSS/JS)
            ├── goal_blk_logo.png   # GOAL logo (dark variant, used in print styles)
            ├── goal_wht_logo.png   # GOAL logo (light variant, used in header/footer)
            ├── netlify.toml        # Netlify build config and security headers
            └── README.md
            ```

            ## Getting Started

            ### Local Development

            No build step is required. Open `index.html` directly in a browser:

            ```bash
            open index.html
            # or use any local server, e.g.
            npx serve .
            ```

            ### Deployment

            The site is configured for Netlify. Push to the connected branch and Netlify will publish the root directory automatically. The `netlify.toml` file sets security headers (`X-Frame-Options`, `X-Content-Type-Options`, `Referrer-Policy`) and long-lived caching for image assets.

            ## Tech Stack

            - **HTML / CSS / JavaScript** — zero dependencies, no build tools
            - - **Google Fonts** — Red Hat Display & Inter
              - - **Netlify** — hosting and header configuration
