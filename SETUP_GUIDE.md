# GitHub Repository Setup Guide
## NYC Airbnb Market Analysis Project

Follow these steps to set up your GitHub repository from scratch.

---

## PART 1: GitHub Account & Repository Creation

### Step 1: Create GitHub Account (if needed)
1. Go to https://github.com
2. Click "Sign up" and create account
3. Verify your email address

### Step 2: Create New Repository
1. Click the **"+"** icon (top right) → "New repository"
2. Fill in details:
   - **Repository name:** `nyc-airbnb-analysis`
   - **Description:** "Seasonal pricing dynamics in NYC Airbnb market - EDA project analyzing 87K listings across 2025"
   - **Visibility:** Public (so recruiters can see it)
   - ✅ Check "Add a README file" (we'll replace it)
   - ✅ Add .gitignore → Select "Python"
   - ✅ Choose a license → Select "MIT License"
3. Click **"Create repository"**

---

## PART 2: Upload Your Files

### Method A: Web Upload (Easiest - No Terminal Required)

1. **On your new repository page:**
   - Click "Add file" → "Upload files"

2. **Drag and drop these files:**
   ```
   ✓ afaqk_Final_Project_90-800.ipynb
   ✓ afaqk_Final_Project_90-800_html.html
   ```

3. **Add commit message:**
   ```
   Add EDA project files - Jupyter notebook and interactive HTML
   ```

4. Click **"Commit changes"**

5. **Upload the README, requirements.txt, and .gitignore:**
   - Click "Add file" → "Upload files" again
   - Upload the three files I created for you:
     * README.md (replace the default one)
     * requirements.txt
     * .gitignore (merge with existing)
   
6. **Commit message:**
   ```
   Add project documentation and dependencies
   ```

7. Click **"Commit changes"**

### Method B: Git Command Line (If you prefer terminal)

```bash
# Navigate to where you want the project
cd ~/Documents

# Clone your repository
git clone https://github.com/YOUR_USERNAME/nyc-airbnb-analysis.git
cd nyc-airbnb-analysis

# Copy your project files here
# (Copy afaqk_Final_Project_90-800.ipynb and .html to this folder)
# (Copy README.md, requirements.txt, .gitignore to this folder)

# Add all files
git add .

# Commit
git commit -m "Add EDA project files and documentation"

# Push to GitHub
git push origin main
```

---

## PART 3: Enable GitHub Pages (Make HTML Interactive)

### Step 1: Configure GitHub Pages
1. In your repository, click **"Settings"** (top navigation)
2. Scroll down left sidebar → Click **"Pages"**
3. Under "Source":
   - Branch: Select **"main"**
   - Folder: Select **"/ (root)"**
4. Click **"Save"**

### Step 2: Wait for Deployment
- GitHub will show: "Your site is ready to be published at..."
- Wait 2-3 minutes for deployment
- Refresh the page - you'll see: "Your site is live at..."

### Step 3: Get Your Live Link
Your HTML will be available at:
```
https://YOUR_USERNAME.github.io/nyc-airbnb-analysis/afaqk_Final_Project_90-800_html.html
```

**Example:** If your username is `afaqkhan`:
```
https://afaqkhan.github.io/nyc-airbnb-analysis/afaqk_Final_Project_90-800_html.html
```

---

## PART 4: Update README with Your Information

### Edit README.md on GitHub:
1. Click on `README.md` in your repository
2. Click the **pencil icon** (top right) to edit
3. Replace placeholders:

   ```markdown
   # Find and replace these:
   
   Line 62: https://yourusername.github.io/nyc-airbnb-analysis/afaqk_Final_Project_90-800_html.html
   → https://YOUR_ACTUAL_USERNAME.github.io/nyc-airbnb-analysis/afaqk_Final_Project_90-800_html.html
   
   Bottom section - Add your contact info:
   - LinkedIn: [Your LinkedIn URL]
   - Email: afaqk@andrew.cmu.edu (or your preferred email)
   - Portfolio: [If you have one]
   ```

4. Click **"Commit changes"**

---

## PART 5: Verify Everything Works

### ✅ Checklist:
- [ ] Repository is public
- [ ] All files uploaded (notebook, HTML, README, requirements.txt)
- [ ] GitHub Pages is enabled
- [ ] HTML link works and shows interactive visualizations
- [ ] README displays correctly with badges
- [ ] Your contact information is updated

### Test Your Links:
1. **Repository:** `https://github.com/YOUR_USERNAME/nyc-airbnb-analysis`
2. **Interactive Report:** `https://YOUR_USERNAME.github.io/nyc-airbnb-analysis/afaqk_Final_Project_90-800_html.html`
3. **Notebook:** Click through on GitHub to view the .ipynb

---

## PART 6: Optional Enhancements

### Add Project to Your GitHub Profile
1. Go to your profile: `github.com/YOUR_USERNAME`
2. Click "Edit profile"
3. Under "Pinned repositories" → Click "Customize your pins"
4. Check the box for `nyc-airbnb-analysis`
5. Save

### Create a Screenshot
1. Take a screenshot of your best visualization (e.g., the Hero Chart)
2. Create folder: `assets/images/` in your repo
3. Upload the screenshot as `hero-chart.png`
4. Add to README under visualizations:
   ```markdown
   ![NYC Airbnb Seasonal Pricing](assets/images/hero-chart.png)
   ```

### Add Topics/Tags
1. On your repository page (main page)
2. Click the gear icon ⚙️ next to "About"
3. Add topics: `data-analysis`, `python`, `airbnb`, `visualization`, `nyc`, `jupyter-notebook`, `eda`, `plotly`, `seaborn`
4. Save

---

## PART 7: Share Your Work

### For Resume/CV:
```
GitHub: github.com/YOUR_USERNAME/nyc-airbnb-analysis
Live Demo: [Your GitHub Pages URL]
```

### For LinkedIn:
Create a post:
```
🎯 Just completed my EDA project analyzing 87K NYC Airbnb listings!

Key Finding: NYC operates as a two-tier market - Manhattan shows 34% seasonal price swings while outer boroughs stay flat.

Built with Python, Plotly, Folium, and 18 custom visualizations.

📊 Live interactive report: [Your GitHub Pages link]
💻 Code & analysis: [Your GitHub repo link]

#DataAnalysis #Python #CMU #HeinzCollege #DataVisualization
```

### For Job Applications:
Include in your cover letter:
```
"I recently completed a comprehensive market analysis of NYC's Airbnb ecosystem 
(87K listings, 18 interactive visualizations), revealing a two-tier pricing 
structure. Full analysis available at: [GitHub Pages link]"
```

---

## 📧 Need Help?

If you run into issues:
1. Check GitHub's documentation: https://docs.github.com
2. GitHub Pages troubleshooting: https://docs.github.com/en/pages
3. The HTML must be in the root directory (not in a subfolder)
4. GitHub Pages can take 5-10 minutes on first deployment

---

## 🎉 You're Done!

Once completed, you'll have:
- ✅ Professional GitHub repository
- ✅ Interactive HTML demo
- ✅ Clean code in Jupyter notebook
- ✅ Comprehensive README
- ✅ Easy sharing links for applications

**Your URLs:**
- **Repo:** `github.com/YOUR_USERNAME/nyc-airbnb-analysis`
- **Live Demo:** `YOUR_USERNAME.github.io/nyc-airbnb-analysis/afaqk_Final_Project_90-800_html.html`
