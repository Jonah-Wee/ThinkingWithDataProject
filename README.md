---
title: "README"
format: gfm
---

# Thinking With Data Project 🎉

Welcome! This page explains everything you need to know to view and use this project — no coding experience needed.

---

## What Is This Project?

This project analyzes data to uncover patterns and insights. All the work is done in **R**, a free tool used by researchers and data scientists, and the results are presented as a clean, readable report.

---

## What You Need to Get Started

### RStudio
RStudio is the app you use to open and run this project.

👉 Download here: [https://posit.co/download/rstudio-desktop](https://posit.co/download/rstudio-desktop)

- Scroll down and click the big **"Download RStudio"** button
- Open the downloaded file and follow the installer instructions

---

## How to Download This Project

You do not need to know anything about GitHub to do this.

1. On this page, look for the green **"Code"** button near the top
2. Click it, then click **"Download ZIP"**
3. Find the downloaded ZIP file (usually in your **Downloads** folder)
4. Double-click the ZIP file to unzip it
5. You should now have a folder called **ThinkingWithDataProject**

---

## How to Open the Project

1. Open **RStudio** (the app you installed above)
2. Go to **File → Open Project**
3. Navigate to the **ThinkingWithDataProject** folder
4. Double-click the file called **ThinkingWithDataProject.Rproj**

RStudio will now open the project automatically.

---

## How to Run the Project

Once the project is open in RStudio:

1. Look at the bottom-left panel — this is called the **Console**
2. Click anywhere in the Console
3. Copy and paste this line, then press **Enter**:
```r
install.packages(c("tidyverse", "quarto"))
```

4. Wait for it to finish (this only needs to be done once)
5. Then in the top-left panel, open the file ending in **`.qmd`**
6. Click the **"Render"** button at the top of that file
7. A report will open automatically in your browser 🎉

---

## Folder Structure

Here is what each file and folder in this project does:

| File / Folder | What it is |
|---|---|
| `ThinkingWithDataProject.Rproj` | The file that opens the project in RStudio |
| `analysis.qmd` | The main analysis file — this generates the report |
| `.gitignore` | A settings file (you can ignore this) |
| `README.qmd` | This file you are reading right now |

---

## How to Use Git (Version Control)

Git is a tool that tracks changes to your files — think of it like a detailed "undo history" for your whole project. GitHub is the website that stores your project online so others can access it.

Here are the basic commands you will use. Open your **Terminal** (Mac: press Cmd + Space and type "Terminal") and type these:

### Check what has changed
```bash
git status
```
Shows you which files have been added, modified, or deleted since your last save.

### Stage your changes
```bash
git add .
```
Tells Git which changes you want to save. The `.` means "everything that changed."

### Commit (save a snapshot)
```bash
git commit -m "describe what you changed here"
```
Saves a snapshot of your project at this point in time. Replace the text in quotes with a short description of what you did, for example `"added introduction section"`.

### Push (upload to GitHub)
```bash
git push
```
Uploads your saved snapshots to GitHub so others can see your latest changes.

### Pull (download latest changes)
```bash
git pull
```
Downloads the latest changes from GitHub to your computer. Always do this before starting work if you are collaborating with others.

---

### The Typical Workflow

Every time you make changes and want to save them to GitHub, follow these four steps in order:
```bash
git pull
git add .
git commit -m "what you changed"
git push
```

Think of it like this:
- **Pull** — check if anyone else made changes first
- **Add** — pick what to save
- **Commit** — take a snapshot
- **Push** — upload it to GitHub

---

## Need Help?

If something is not working, here are some things to try:

- Make sure you opened the **`.Rproj` file** and not just a random file in the folder
- Try restarting RStudio and running the `install.packages` step again
- For Git issues, make sure you are in the right folder in Terminal before running commands (`cd ~/path/to/ThinkingWithDataProject`)
