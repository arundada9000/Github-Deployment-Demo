#  GitHub Pages Deployment Demo

This repository demonstrates **all the ways you can deploy a website using GitHub Pages** - including deployment from the main branch, a subfolder, and a separate branch.

It’s a perfect example setup for tutorials or testing GitHub Pages behavior.

---

##  Overview

| Demo                  | Branch     | Folder  | Description                                          |
| --------------------- | ---------- | ------- | ---------------------------------------------------- |
|  **Root Site**      | `main`     | `/`     | Deployed from the **root folder** of the main branch |
|  **Subfolder Site** | `main`     | `/docs` | Deployed from a **subfolder** of the main branch     |
|  **Branch Site**    | `gh-pages` | `/`     | Deployed from a **different branch** (`gh-pages`)    |

Each version contains its own simple HTML/CSS project so you can clearly see which deployment is currently active.

---

##  Folder Structure

```

github-pages-demo/
│
├── index.html # Root site (main branch)
├── style.css
│
├── docs/ # Subfolder site
│ ├── index.html
│ └── style.css
│
└── (gh-pages branch) # Separate branch site
├── index.html
└── style.css

```

---

## ⚙ How to Use This Repository

### 1⃣ Clone the Repository

```bash
git clone https://github.com/<your-username>/github-pages-demo.git
cd github-pages-demo
```
---

## License

This project is for educational and personal learning purposes only. Commercial use, public deployment, or any revenue-generating use requires explicit written permission from the author. See [LICENSE](LICENSE) for details.
