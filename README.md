# 📂 Denali AI File Renamer: Your Files, Evolved

Denali AI is a groundbreaking plugin that leverages the power of Artificial Intelligence to bring intelligent automation to your file management workflow. In today's digital world, our notes and documents are the bedrock of our knowledge, but they often become a tangled mess of generic or confusing names like "Untitled 2.md" or "My_Project_Final_v3.docx". This is where Denali AI steps in. It goes beyond simple automation by analyzing the actual content of your files to suggest not just a descriptive name, but also rich, meaningful metadata, creating a truly smart and self-organizing knowledge base. Without AI, this level of contextual understanding is simply not possible; you'd be stuck with rigid, rule-based systems that can't comprehend nuance. Denali AI transforms your digital chaos into a structured, searchable, and elegant system, freeing you to focus on creating, not organizing.

---

### ✨ Real, High-Value Benefits

* **Intelligent Naming**: The AI understands the context of your file's content to generate a logical, descriptive, and human-readable filename, instantly making your files more discoverable.
* **Automated Frontmatter**: It automatically enriches your note's frontmatter with key properties like `title`, `author`, `project`, and `tags`, turning a simple note into a fully-fledged, well-documented artifact.
* **Time-Saving Automation**: Whether it's a single note or an entire folder of unsorted files, Denali AI can process them in seconds, saving you hours of tedious manual work.
* **Preserved Links**: When you rename a file, the plugin intelligently adds the old name as an alias, ensuring that all existing links to the file remain valid and unbroken.

---
### Support
Please reach out to denali_ai_dev_team [at] tutivsoft.com for support.  We will fully resolve all queries within 24 hours.

### 💰 Plans & Pricing

Denali AI operates on a simple, one-time credit system. You buy credits and use them as you go, with no subscriptions, hidden fees, or recurring charges.

| Feature | Free Plan | Pro Plan (0.99 USD) | Ultimate Plan (9.99 USD) |
| :--- | :--- | :--- | :--- |
| **Cost** | Free | 0.99 USD | 9.99 USD |
| **Credits Included** | 10 Free Credits | 25 Credits | 500 Credits |
| **Max AI Input Length** | 1,000 characters | 3,000 characters | 10,000 characters |
| **Max AI Output Length** | 50 characters | 500 characters | 1,000 characters |

**Need more credits?** You can easily top up your balance. Each file rename costs 1 credit, and each AI-generated frontmatter change (e.g., adding a title or an author) also costs 1 credit.

* **25 Credits (USD 0.99)** - Buy Here
* **500 Credits (USD 9.99)** - Buy Here
* **25 Credits (INR 079)** - Buy Here
* **500 Credits (INR 799)** - Buy Here

---

### 🛠️ How to Use

Denali AI is designed for simplicity. Once installed and configured, you have two primary ways to use it.

1.  **For a Single File**:
    * Right-click on any `.md` file in the file explorer.
    * Select `Rename File with Denali AI`.
    * Depending on your settings, a modal will appear with a suggested new name, or the file will be renamed automatically.

2.  **For an Entire Folder**:
    * Right-click on any folder in the file explorer.
    * Select `Batch Rename Folder with Denali AI`.
    * The plugin will automatically go through all markdown files in the folder (and its subfolders) and apply the renaming process. You can optionally configure it to only target "untitled" files.

**Pro-Tip**: You can also use the command palette (`Ctrl/Cmd + P`) and search for `Denali AI` to access the main commands.

---

### 🎙️ Testimonials

"This tool is a game-changer! I used to dread organizing my notes after a big project. Now, I just run the batch rename and everything is perfectly organized. The AI suggestions are incredibly accurate!"
— **Sarah K., Project Manager at a Tech Startup**

"As a freelance writer, my folders were a mess of rough drafts and final versions. Denali AI not only cleans up the file names but also adds useful tags to my notes, making it so much easier to find and reference old work."
— **Michael R., Freelance Writer**

"I've tried a dozen different renaming tools, but none of them had the intelligence of Denali AI. It's like having a personal assistant for my digital library. The `addAlias` feature alone has saved me from so many broken links."
— **Emily C., UX Designer at a Digital Agency**

---

### 🚀 Key Features

* **AI-Powered File Naming**: The plugin uses AI to analyze your file's content and generate a descriptive, relevant, and human-readable filename.
* **Frontmatter Enrichment**: It automatically adds useful metadata to your note's frontmatter, such as a title, author, project, status, and tags, transforming a simple note into a structured and searchable document.
* **Automatic & Interactive Modes**: You can choose to either have the plugin automatically rename files without any input or use the interactive mode, which presents a modal window for you to review and edit the suggested filename before applying the changes.
* **Batch Processing**: The plugin can process an entire folder of markdown files at once, saving you significant time and effort.
* **Backup & Logging**: Before any changes are made, the plugin can create a backup of your original file. It also maintains a log of all renaming operations, helping you keep track of your changes.
* **Link Preservation**: The original file name is automatically added as an alias in the frontmatter, ensuring that any existing links to the file remain valid after the rename.

---

### ⚙️ Settings & Customization

The plugin's behavior can be extensively customized through the settings pane.

#### **Main Workflow**

* **Rename Process Choice**: Select between **Automatic** (no user interaction) or **Interactive** (shows a modal to approve/edit).
* **Rename on Creation**: Automatically triggers the renaming process when a new file is created.
* **Only Rename Untitled Files**: Restricts renaming to files with specific keywords in their name (e.g., "Untitled").
* **Untitled Keywords**: A comma-separated list of keywords that identify an untitled file.
* **Auto Subfolder**: The AI will suggest and create a new subfolder based on the file's content and move the file there.

#### **AI & API**

* **AI Name Style**: Choose a style for the AI-generated name:
    * **Balanced**: Human-readable, title-cased names (e.g., `Apple Inc Annual Report for 2025`).
    * **Keyword-Filled**: A dense list of keywords (e.g., `Code Python Tensorflow Johsnson AI Project memory second fix`).
    * **Niche Words Only**: Focuses on specific, unique terms (e.g., `apple report 2025 john reviewed approved emergency fix2`).
* **Max Input Length**: The maximum number of characters from your note that will be sent to the AI for analysis.
* **Max Output Length**: The maximum number of characters for the final filename.

#### **File Naming & Structure**

* **File Name Case**: Convert the AI's suggestion to **kebab-case**, **camelCase**, or **lowercase**. You can also keep the **Original** case.
* **Add Timestamp to New File**: Adds a timestamp (`YYYY-MM-DD HH-MM-SS`) to the filename, either as a **Prefix** or **Suffix**.
* **Stop Words**: A comma-separated list of words to automatically remove from the generated name.
* **Character Replacement**: Specify a single character (e.g., `-` or `_`) to replace spaces in the filename.

#### **Frontmatter Automation**

* **Include Frontmatter**: Sends existing frontmatter to the AI for better contextual understanding.
* **Add Alias**: Adds the old filename as an `alias` in the frontmatter.
* **Add Title**: Adds a `title` property to the frontmatter. The title is intelligently derived from the AI-generated filename.
* **Add Created Date**: Adds a `created` property with the file's creation date. You can specify the date format.
* **Add Modified Date**: Adds a `modified` property with the file's last modified date. You can specify the date format.
* **Add Author**: The AI will suggest and add an `author` property.
* **Add Status**: Adds a `status` property with a default value of your choice.
* **Add Project**: The AI will suggest and add a `project` property.
* **Add Topic**: The AI will suggest and add a single, broad `topic` property.

#### **Backup & Log**

* **Create Backups**: Toggles whether a copy of the original file is made before renaming.
* **Backup Folder**: The path where backup files are saved.
* **Backup Timestamp Format**: Choose a timestamp format for your backup files.
* **Enable Logs**: Toggles the display of logs in the modal window and the console.
* **Save Logs to File**: Saves all renaming actions to a log file within the backup folder.
* **Log Window Close Delay**: Sets the number of seconds the log window will remain open after a process is complete.

---
# obsidian-denali-ai-file-renamer-front-matter
Obsidian plugin to rename notes and enrich front matter - concise, human-readable, keyword-rich. Auto populate title, tags, summary, and more from your note's content.
