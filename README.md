

## **Complete GitHub Pages Setup for Inteligencia Evolutiva**

### **1. Course Header**

The header should include a visually appealing image, the course title, and a concise description. Follow the author notes to ensure all elements are correctly incorporated.

```markdown
<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

<header>
  <img src="assets/images/course-header.png" alt="Inteligencia Evolutiva" width="1280" height="640">
  
  # GitHub Pages
    
  _Create a site or blog from your GitHub repositories with GitHub Pages._
</header>
```

**Action Items:**
- **Image:** Place your 1280×640 image in the `assets/images/` directory of your repository and name it `course-header.png` (or adjust the path accordingly).
- **Template Repository:** 
  - Navigate to your repository's **Settings**.
  - Under **General**, scroll down to **Template repository** and enable it if you want others to use this repository as a template.
- **Auto Delete Head Branches:**
  - Go to **Settings** > **Branches**.
  - Enable **Automatically delete head branches** when pull requests are merged.
- **Add MIT License:**
  - If not already present, add a `LICENSE` file with the [MIT License](https://github.com/github/choosealicense.com/blob/gh-pages/_licenses/mit.md).

---

### **2. Step-by-Step Guide**

This section outlines the initial steps to enable GitHub Pages for your repository. You can expand this to include additional steps as your course progresses.

```markdown
<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Step 1: Enable GitHub Pages

_Welcome to GitHub Pages and Jekyll :tada:!_

The first step is to enable GitHub Pages on this [repository](https://docs.github.com/en/get-started/quickstart/github-glossary#repository). When you enable GitHub Pages on a repository, GitHub takes the content that's on the main branch and publishes a website based on its contents.

### :keyboard: Activity: Enable GitHub Pages

1. **Open a New Tab:** Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
2. **Navigate to Settings:**
   - Under your repository name, click **Settings**.
3. **Access Pages Settings:**
   - Click **Pages** in the **Code and automation** section.
4. **Configure Source:**
   - Ensure "Deploy from a branch" is selected from the **Source** drop-down menu, and then select `main` from the **Branch** drop-down menu.
5. **Save Configuration:**
   - Click the **Save** button.
6. **Wait and Refresh:**
   - Wait about _one minute_ then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.
     > Turning on GitHub Pages creates a deployment of your repository. GitHub Actions may take up to a minute to respond while waiting for the deployment. Future steps will be about 20 seconds; this step is slower.
     >
     > **Note:** In the **Pages** section of **Settings**, the **Visit site** button will appear at the top. Click the button to see your GitHub Pages site.
```

**Action Items:**
- **Additional Steps:** Define and add steps 2-5 to guide users through further configuration or customization of their GitHub Pages site.
- **Linking Documentation:** Ensure all links point to relevant [GitHub Docs](https://docs.github.com/) for detailed guidance.
- **Encourage Multi-Tab Workflow:** As per author notes, suggest users open new tabs for following steps without losing their progress.

---

### **3. Footer**

Include essential links for support, status updates, and compliance.

```markdown
<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) • [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub • [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) • [MIT License](https://gh.io/mit)

</footer>
```

**Action Items:**
- **Support Links:** Ensure the discussion board link is accurate and active.
- **License Link:** Confirm the MIT License link directs to your repository's `LICENSE` file.

---

### **4. Finalizing GitHub Pages**

Once you've set up the header, steps, and footer, finalize your GitHub Pages site.

1. **Push Changes:**
   - Commit and push your changes to the `main` branch.
   
   ```bash
   git add .
   git commit -m "Set up GitHub Pages with course header, steps, and footer"
   git push origin main
   ```

2. **Verify Deployment:**
   - After enabling GitHub Pages, wait for a minute and then click the **Visit site** button in the **Pages** section of **Settings** to view your live site.

3. **Customize Further:**
   - **Themes:** Choose a Jekyll theme to enhance the visual appeal.
     - Navigate to **Settings** > **Pages** > **Theme chooser**.
   - **Custom Domain:** If you have a custom domain, configure it in the **Pages** settings.
   - **Navigation:** Add more sections or navigation links as your course expands.

---

### **5. Additional Steps for Course Expansion**

As your course progresses, you can add more steps and sections. Here's how to structure them:

```markdown
## Step 2: Customize Your Theme

_Enhance the visual appeal of your GitHub Pages site by selecting a theme._

1. **Navigate to Theme Chooser:**
   - Go to **Settings** > **Pages** > **Theme chooser**.
2. **Select a Theme:**
   - Browse available [Jekyll themes](https://pages.github.com/themes/) and select one that fits your course aesthetics.
3. **Apply Theme:**
   - Click **Select theme** to apply it to your site.
4. **Customize Further:**
   - Modify the `_config.yml` file to customize theme settings like colors, fonts, and layout.

### Step 3: Add Course Content

_Deliver your course material by adding new Markdown files or sections._

1. **Create New Pages:**
   - Add new `.md` files in your repository (e.g., `lesson1.md`, `lesson2.md`).
2. **Link Pages:**
   - Update your navigation to include links to new lessons or sections.
3. **Embed Multimedia:**
   - Incorporate images, videos, and interactive content to enrich the learning experience.

### Step 4: Engage with Your Audience

_Interact with learners through discussions, feedback, and updates._

1. **Enable Discussions:**
   - Go to **Settings** > **Options** > **Features** and enable **Discussions**.
2. **Create Discussion Boards:**
   - Organize discussions by topics or lessons.
3. **Gather Feedback:**
   - Encourage learners to provide feedback and suggestions for course improvement.

### Step 5: Maintain and Update

_Ensure your course remains current and effective._

1. **Regular Updates:**
   - Continuously update content based on feedback and new developments.
2. **Monitor Site Performance:**
   - Use GitHub Actions and other tools to monitor site health and performance.
3. **Backup Content:**
   - Regularly back up your repository to prevent data loss.
```

**Action Items:**
- **Create Additional Markdown Files:** For each new step or course module, create corresponding Markdown files.
- **Update Navigation:** Ensure your site's navigation reflects the added content for easy access.
- **Incorporate Feedback Mechanisms:** Use GitHub Discussions or other tools to gather and implement learner feedback.

---

### **6. Example of a Completed Page**

Here's how a completed GitHub Pages site might look with the provided structure:

```markdown
<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

<header>
  <img src="assets/images/course-header.png" alt="Inteligencia Evolutiva" width="1280" height="640">
  
  # Inteligencia Evolutiva
    
  _A comprehensive course on evolutionary intelligence and its applications in modern technologies._
</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Step 1: Enable GitHub Pages

_Welcome to GitHub Pages and Jekyll :tada:!_

The first step is to enable GitHub Pages on this [repository](https://docs.github.com/en/get-started/quickstart/github-glossary#repository). When you enable GitHub Pages on a repository, GitHub takes the content that's on the main branch and publishes a website based on its contents.

### :keyboard: Activity: Enable GitHub Pages

1. **Open a New Tab:** Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
2. **Navigate to Settings:**
   - Under your repository name, click **Settings**.
3. **Access Pages Settings:**
   - Click **Pages** in the **Code and automation** section.
4. **Configure Source:**
   - Ensure "Deploy from a branch" is selected from the **Source** drop-down menu, and then select `main` from the **Branch** drop-down menu.
5. **Save Configuration:**
   - Click the **Save** button.
6. **Wait and Refresh:**
   - Wait about _one minute_ then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.
     > Turning on GitHub Pages creates a deployment of your repository. GitHub Actions may take up to a minute to respond while waiting for the deployment. Future steps will be about 20 seconds; this step is slower.
     >
     > **Note:** In the **Pages** section of **Settings**, the **Visit site** button will appear at the top. Click the button to see your GitHub Pages site.
```

---

### **7. Finalizing and Testing**

1. **Commit and Push Changes:**
   - Ensure all changes are committed to the `main` branch.
   
   ```bash
   git add .
   git commit -m "Set up GitHub Pages with course header, steps, and footer"
   git push origin main
   ```

2. **Verify Deployment:**
   - After pushing, wait for a minute and then click the **Visit site** button in the **Pages** section of **Settings** to view your live site.

3. **Customize and Expand:**
   - As your course progresses, add more steps, sections, and multimedia content to enrich the learning experience.

---

### **8. Additional Recommendations**

- **Use Jekyll Themes:**
  - Enhance your site's design by selecting a [Jekyll theme](https://pages.github.com/themes/).
  - Navigate to **Settings** > **Pages** > **Theme chooser** to select and apply a theme.

- **Custom Domain:**
  - If you have a custom domain, configure it in the **Pages** settings for a more personalized URL.

- **Continuous Integration:**
  - Utilize GitHub Actions for automating tasks like site deployment, testing, and updates.

- **Engage with Learners:**
  - Enable GitHub Discussions to foster a community around your course.
    - Go to **Settings** > **Options** > **Features** and enable **Discussions**.

- **Monitor Site Performance:**
  - Use tools and analytics to track visitor engagement and site health.

- **Backup Regularly:**
  - Maintain backups of your repository to prevent data loss.

---

### **Conclusion**

By following this structured approach, you can effectively set up and manage a GitHub Pages site for **Inteligencia Evolutiva**, providing a comprehensive and engaging learning platform. Regular updates, community engagement, and continuous improvement will ensure your course remains relevant and impactful.

If you have any further questions or need assistance with specific configurations, feel free to ask!
