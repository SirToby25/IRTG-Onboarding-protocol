# IRTG-Onboarding-protocol

Welcome! This repository contains the **Onboarding Protocol** project written in LaTeX. This README explains how to set up your environment, contribute to the project, and compile the PDF.

---

In case the following seems to complicated, just send me your changed files per mail and I will contribute them for you.

---

## 1. Prerequisites

- **Git** installed on your computer  
- **LaTeX distribution** (TeX Live, MikTeX, or MacTeX)  
- **LuaLaTeX** (recommended compiler)  
- **SSH key** set up in your GitHub account (or a personal access token if using HTTPS)

---

## 2. Clone the Repository

**Using SSH (recommended):**

```bash
git clone git@github.com:yourusername/IRTG-Onboarding-protocol.git
cd IRTG-Onboarding-protocol
```

**Using HTTPS:**

```bash
git clone https://github.com/yourusername/IRTG-Onboarding-protocol.git
cd IRTG-Onboarding-protocol
```

---

## 3. Setting Up Git Authentication

**Using SSH**

1.) Generate an SSH key if you don’t have one already. Otherwise you can just use your exiting one and continue with 3.):

```bash
ssh-keygen -t github -C "your_email@example.com"
```

2.) Add your public key (id\_github.pub) to your GitHub account under Settings -> SSH and GPG keys (copy and paste).

3.) Add the key to your SSH agent:

```bash
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_github
```

---

## 4. Compiling the LaTeX Project

- Open the project in your preferred LaTeX editor.
- Use LuaLaTeX to compile main.tex.

## 5. Contribution work flow

1.) Create branches for your changes

```bash
git checkout -b name_of_branch
```

2.) Make changes, then stage and commit them:

```bash
git add .
git commit -m "Describe your changes"
```

3.) Push your branch to github

```bash
git push -u origin name_of_branch
```

4.) Create a **Pull Request(PR)** on Github to merge your changes into main.

5.) Frequently check for updates and pull them:

```bash
git pull origin main
```
