# Week 2 Attendance: Project Prep Site Setup & Content Generation

## Overview
For your course project, you will build a multi-page website on a topic of your choice. In this step, you will set up your workspace, research your topic, and use Generative AI to create the raw text content for your site.

### Step 1: Create Your Project Folder
1.  Inside your main repository folder (`your-pri`), create a new folder (e.g., `project`).
---

## Instructions

### Step 2: Open the "Sandbox" (The Specific Folder)
*Choose the instructions that match your setup:*

#### ☁️ Option A: For GitHub Codespaces Users
1.  Launch your Codespace as usual.
2.  Go to **File > Open Folder...** (top left menu).
3.  In the command palette that appears at the top, click `your-pri`, then click the specific week folder (e.g., `project`).
4.  Click **OK**.
5.  *The page will reload.* This is normal! When it comes back, your sidebar (Explorer) should **only** show the files inside `project`.

#### 💻 Option B: For Local VS Code Users (Desktop)
1.  Open VS Code on your computer.
2.  Go to **File > Open Folder...**
3.  Navigate to your repository folder (`your-pri`).
4.  Select the specific week folder (e.g., `project`) and click **Open** (or **Select Folder**).
5.  **Check:** Your sidebar (Explorer) should **only** show the files inside `project`.


### Step 3: Research Phase
Before asking AI to write your content, do some quick research to make your site unique.
1.  **Pick a Topic:** Choose something you are interested in (e.g., "Gourmet Coffee," "Local Hiking Trails," "Indie Game Dev").
2.  **Gather Inspiration:** Look at 2-3 existing websites on this topic.    
    * *What headings do they use?*
    * *What kind of lists do they have?* (e.g., "Top 10 Beans," "Gear Checklist").
3.  **Identify Key Info:** Note down **3 specific facts or sections** you definitely want on your site.

### Step 4: Create the Plan
1.  **Create File:** Create a new file named `README.md` inside your `project` folder.
2.  **Add Content:** Use the following Markdown syntax to structure your plan at the top of the file:
    * **Heading 1:** Use `#` for your project name (e.g., `# Project: The Coffee Explorer`).
    * **Bold Text:** Use `**` for the labels (e.g., `**Description:**`).
    * **List:** Use `1.` or `-` for your research points.

    *Example content to type:*
    ```markdown
    # Project: [Your Topic Name]
    
    **Description:** [Your 1-2 sentence summary]
    
    **Key Facts/Inspiration:**
    1. [Fact 1]
    2. [Fact 2]
    3. [Fact 3]
    ```

3.  **Commit Your Work:**
    * Complete the git workflow and commit with the message: `Project: Initial setup and research plan`

### Step 5: Generate Content with AI
Now, use an AI tool (ChatGPT, Gemini, etc.) to generate the raw text for **2 separate pages** (e.g., a "Home" page and an "About" or "Services" page).

**Prompt Requirement:**
Your prompt must use the research you did in Step 2. Ask for:
* A catchy **Main Heading**.
* **Descriptive Text** (2-3 paragraphs).
* A **List**.

**Example Prompt:**
> "I am building a website about [Your Topic]. Based on my research, I want to focus on [Fact 1] and [Fact 2].
>
> Please generate content for a 'Home' page. It should include a catchy H1 title, two paragraphs of introduction, and a bulleted list of [Your List Idea].
>
> Then, do the same for an 'About' page focusing on [Fact 3]."


### Step 6: Document Your Content
1.  **Document Page 1:**
    * In `README.md`, add a heading: `## Page 1: Home`.
    * Copy the AI content for the home page.
    * Paste it below the heading inside **Triple Backticks** (code block).

2.  **Document Page 2:**
    * Add a new heading: `## Page 2: About` (or your second page name).
    * Copy the AI content for the second page.
    * Paste it below the heading, again ensuring you use **Triple Backticks**.

3.  **Add AI Link:**
    * At the bottom of the file, add a heading `## AI Session Link`.
    * Paste the "Share Link" to your chat session.

    *Example content to type:*
    ```markdown
    ## Page 1: Home
    ```text
    (Paste AI Content Here)
    Welcome to Coffee Explorer!
    ...
    * Expert Reviews
    ```

    ## Page 2: About
    ```text
    (Paste AI Content Here)
    Our Mission
    ...
    1. Sustainability
    ```text
    ## AI Session Link
    [Link to AI Chat](https://chat.openai.com/share/...)
    ```

4.  **Commit Your Work:**
    * Perform a commit with the message: `Project: Generated page content with AI`