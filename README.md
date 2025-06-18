# 📚 FETP Sierra Leone

This project contains a collection of Jupyter Notebooks organized into units, which are converted into a static website using **Jupyter Book** and deployed via **GitHub Pages**. The repository is designed to help non-technical users easily contribute, make edits using VS Code, and have their changes reflected online via an automated deployment pipeline.

---

## 📁 Project Structure

```plaintext
📁 .github/
│   └── workflows/
│       └── deploy.yml        # GitHub Actions workflow for automatic deployment
📁 build/                     # Auto-generated folder for built static site
📁 images/                    # Images used in notebooks (e.g., charts, diagrams)
📄 toc.yml                   # Table of contents file for Jupyter Book
📄 requirements.txt          # Python dependencies required for running/building
📄 unit1.ipynb               # Tutorial notebook (Unit 1)
📄 unit2.ipynb               # Tutorial notebook (Unit 2)
...
📄 unit8.ipynb               # Tutorial notebook (Unit 8)


🧠 Purpose of Each Component

Path/File	Description
.github/workflows/	Contains GitHub Actions workflows to automate building & deployment
build/	Holds the output of the Jupyter Book build process (can be auto-generated)
images/	Central place for all images used in notebooks
requirements.txt	Lists required Python packages like jupyter-book
toc.yml	Controls notebook order & structure of the site
unitX.ipynb	Educational notebook files containing markdown, code, and visuals


🚀 How It Works
Contributors edit notebooks in VS Code.

They commit and push changes to GitHub.

GitHub Actions runs the workflow in .github/workflows/.

The site is built and deployed to GitHub Pages automatically.


📌 Notes
You don’t need to manually run build commands — everything happens through GitHub Actions.

Make sure all image paths in notebooks are relative (e.g., images/mychart.png).

Use toc.yml to control which notebooks show up in the navigation bar of the site.

