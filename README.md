# SisLove US - Premium Pajama & Loungewear Website

A modern, premium-quality boutique website built for SisLove US. This project features a luxury aesthetic, responsive design, and smooth animations, tailored for high-end pajamas and loungewear.

## Project Structure

```text
├── index.html          # Main HTML structure with semantic elements
├── css/
│   └── style.css       # Custom premium styles, variables, and animations
├── js/
│   └── script.js       # Interactivity, counters, and form validation
├── images/             # Local images directory
└── README.md           # Project documentation
```

## Features

- **Premium Design:** Luxury aesthetic with a professional blue, white, pink, and creamy yellow color palette.
- **Fully Responsive:** Optimized for desktop, tablet, and mobile devices.
- **Interactive Elements:**
  - Sticky navigation bar
  - Mobile-responsive menu
  - Animated statistics counters for brand values
  - Scroll-reveal animations
  - Smooth scrolling for anchor links
  - Functional "Scroll to Top" button
- **Collection Showcase:** Beautifully designed cards for pajama sets.
- **Quote Request:** Comprehensive form with client-side validation and visual feedback.
- **Accessibility:** Semantic HTML, ARIA labels, and keyboard-friendly navigation.
- **SEO Optimized:** Meta tags, Open Graph tags, and structured content for brand visibility.

## How to Run Locally

1. Clone or download the repository.
2. Open `index.html` in any modern web browser.
3. No build step or local server is required as it uses vanilla HTML/CSS/JS.

## Deployment Instructions

### GitHub Pages
1. Push the code to a GitHub repository.
2. Go to **Settings** > **Pages**.
3. Under **Build and deployment**, select the `main` branch and the `/ (root)` folder.
4. Click **Save**. Your site will be live at `https://<username>.github.io/<repo-name>/`.

### Netlify
1. Log in to Netlify and click **Add new site** > **Import an existing project**.
2. Connect your GitHub/GitLab account and select the repository.
3. Leave the build command and publish directory empty (it will default to the root).
4. Click **Deploy [Site Name]**.

### Vercel
1. Log in to Vercel and click **Add New** > **Project**.
2. Import the repository from your Git provider.
3. Vercel will automatically detect the project type.
4. Click **Deploy**.

## Custom Domain
To connect a custom domain later:
1. Purchase a domain from a provider (e.g., Namecheap, Google Domains).
2. In your deployment platform (GitHub Pages, Netlify, or Vercel), find the **Domain Settings** section.
3. Add your custom domain and follow the instructions to update your domain's DNS records (CNAME, A records).
