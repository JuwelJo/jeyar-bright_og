# JEYAR BRIGHTECH - Premium Solar Energy Website

A modern, high-performance, responsive, and SEO-friendly website for **JEYAR BRIGHTECH**, a premium residential solar installation company servicing Thiruvananthapuram, Kerala. 

This website features a serene coastal theme with interactive calculations, spec comparison lists, local maps, and a cinematic live background video loop.

---

## 🌟 Key Features

*   **Cinematic Live Video Loop**: Features a high-definition looping background video (`beach_video.mp4`) showing moving clouds, soaring birds, and water wave shimmers.
*   **Twilight & Dawn Transitions**: Click the Sun/Moon toggle to trigger a slow, 2.2-second transition where background sky gradients and UI cards dim and adjust for night/day cycles.
*   **Interactive Solar Calculator**: An real-time savings estimator allowing users to adjust their monthly electricity bill to calculate recommended system size (kWp), monthly savings (INR), required roof space (sq. ft.), and investment payback periods.
*   **Specifications Table**: A clean comparison table displaying brands (PAHAL, Selec, L&T, Havells, Excel) and warranty terms (up to 30 years) for the featured 5 kW solar plant.
*   **Thiruvananthapuram Contact Channels**: Direct clickable telephone links, custom WhatsApp redirection interfaces, and a integrated responsive Google Maps location.
*   **Modern Glassmorphism UI**: Built with transparent cards (`15%` opacity, `24px` backdrop blur) and smooth CSS animations that scale and respond beautifully on mobile devices.

---

## 🛠️ Tech Stack & Structure

*   **HTML5**: Semantic and SEO-friendly structure.
*   **CSS3**: Custom properties (variables), transitions, and keyframe animations.
*   **JavaScript (Vanilla)**: Interactivity, sliders, stat counters, accordion FAQ triggers, and validation handlers.
*   **No Build Step Needed**: Files are completely static and hostable out-of-the-box on any static provider (GitHub Pages, Vercel, Netlify).

---

## 🚀 How to Host on GitHub Pages (Free Hosting)

Follow these simple steps to deploy this website online using GitHub Pages:

### Step 1: Create a GitHub Repository
1. Log in to your account at [GitHub](https://github.com).
2. Click the **New** button to create a new repository.
3. Name it (e.g., `jeyar-brightech`) and keep it **Public**.
4. Leave "Add a README", ".gitignore", and "License" unchecked (since we already have them). Click **Create repository**.

### Step 2: Upload Project Files
Upload the project files directly using GitHub's web interface or Git command line:
#### Method A: Using the GitHub Website (Easiest)
1. In your new repository page, click the link **"uploading an existing file"** near the top.
2. Drag and drop all the files from this folder:
   *   `index.html`
   *   `style.css`
   *   `app.js`
   *   `README.md`
   *   `.gitignore`
   *   `assets/` (make sure the entire assets folder is uploaded with its contents)
3. Wait for the upload to finish, write a commit message (e.g., `Initial commit`), and click **Commit changes**.

#### Method B: Using Git Command Line
```bash
git init
git add .
git commit -m "Initial commit of Jeyar Brightech website"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub and click on **Settings** (tab at the top).
2. In the left sidebar, scroll down and click **Pages**.
3. Under the **Build and deployment** section:
   *   **Source**: Select `Deploy from a branch`.
   *   **Branch**: Select `main` (or `master`) and change the folder dropdown from `/docs` to `/ (root)`.
4. Click the **Save** button.

🎉 **You are done!** In about 1–2 minutes, refresh the page. You will see a blue banner at the top of the Pages settings showing your live URL:
`https://<your-username>.github.io/<your-repo-name>/`
