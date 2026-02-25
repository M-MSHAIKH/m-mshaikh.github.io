# Mohammad Aadil Shaikh — Personal Portfolio Website

A professional portfolio website focused on **ADAS & Control Engineering**, built with pure HTML, CSS, and JavaScript. Designed for hosting on **GitHub Pages**.

## 🌐 Live Site

Once deployed: `https://M-MSHAIKH.github.io`

---

## 📁 Project Structure

```
github_page_website/
├── index.html          # Home / Landing page
├── about.html          # About, Education, Coursework
├── projects.html       # Project portfolio (Featured + Grid)
├── skills.html         # Technical skills & tools
├── experience.html     # Work experience & awards
├── contact.html        # Contact information & form
├── css/
│   └── style.css       # Dark theme stylesheet
├── js/
│   └── main.js         # Animations & interactivity
├── images/             # (Create this folder for your images)
│   └── profile.jpg     # Your professional photo
└── README.md           # This file
```

---

## 🚀 How to Deploy on GitHub Pages (Step-by-Step)

### Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in to your account (`M-MSHAIKH`).
2. Click the **"+"** button (top right) → **"New repository"**.
3. Name it exactly: **`M-MSHAIKH.github.io`**
   - This special naming convention tells GitHub to host it as your personal site.
4. Set it to **Public**.
5. Do **NOT** initialize with a README (we already have one).
6. Click **"Create repository"**.

### Step 2: Push Your Code

Open your terminal in this project folder and run:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Create your first commit
git commit -m "Initial commit: ADAS & Control Engineering portfolio"

# Set the branch name to main
git branch -M main

# Add your GitHub repository as remote
git remote add origin https://github.com/M-MSHAIKH/M-MSHAIKH.github.io.git

# Push to GitHub
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub: `https://github.com/M-MSHAIKH/M-MSHAIKH.github.io`
2. Click **"Settings"** (tab at the top).
3. Scroll down to **"Pages"** in the left sidebar.
4. Under **"Source"**, select **"Deploy from a branch"**.
5. Select branch: **main**, folder: **/ (root)**.
6. Click **Save**.
7. Wait 1-2 minutes, then visit: **`https://M-MSHAIKH.github.io`**

---

## ✏️ How to Customize

### Add Your Photo
1. Create an `images/` folder in the project root.
2. Add your professional photo as `images/profile.jpg`.
3. In `about.html`, replace the placeholder div with:
   ```html
   <img src="images/profile.jpg" alt="Mohammad Aadil Shaikh">
   ```

### Enable Contact Form
The contact form needs a backend service (GitHub Pages only serves static files). 
1. Go to [formspree.io](https://formspree.io) and create a free account.
2. Create a new form and copy your Form ID.
3. In `contact.html`, replace `YOUR_FORM_ID` in the form action:
   ```html
   <form action="https://formspree.io/f/YOUR_ACTUAL_ID" method="POST">
   ```

### Add Project Images
For each project, you can add screenshots or diagrams:
1. Save images to `images/projects/`.
2. Add `<img>` tags inside project cards.

### Update Content
All content is in plain HTML — just edit the text directly in the `.html` files.

---

## 🎨 Design Features

- **Dark engineering theme** with cyan/purple accents
- **Animated skill bars** that fill on scroll
- **Typing effect** on the hero page cycling through roles
- **Smooth page transitions** between pages
- **Responsive design** for mobile, tablet, and desktop
- **Grid background pattern** for a technical aesthetic
- **Intersection Observer** scroll animations

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure & content |
| CSS3 | Styling, animations, responsive design |
| Vanilla JavaScript | Interactivity, scroll effects |
| Google Fonts | Inter + JetBrains Mono typography |
| GitHub Pages | Free hosting |

---

## 📝 Future Enhancements

- [ ] Add a **Blog** section for technical articles (e.g., "EKF vs UKF for Vehicle State Estimation")
- [ ] Add **project demo videos** or GIF animations
- [ ] Integrate **Google Analytics** for visitor tracking
- [ ] Add a **downloadable CV** (PDF) link
- [ ] Set up a **custom domain** (e.g., `aadilshaikh.com`)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
