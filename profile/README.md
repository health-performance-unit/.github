# 🏥 Welcome to the Health Performance Unit (HPU) Central Hub!

Think of this GitHub Organization as our **Secure Google Drive** for Code and Apps. This is the central vault where all HPU digital projects, dashboards, and software are safely stored, tracked, and shared among the team.

---

## ⏱️ The 30-Second Cheat Sheet (Glossary)
If you are new to GitHub, just remember these 4 words:
* 📁 **Repository (Repo):** A project folder. Every dashboard or app gets its own Repo.
* ☁️ **Push:** Uploading your saved work to this cloud vault so the team can see it.
* 📥 **Pull:** Downloading the newest updates your team made from the cloud to your laptop.
* ⏪ **Commit/Revert:** A "Save State". GitHub acts like a Time Machine. Every time you **save** (commit), you can always **rewind** (revert) if you make a mistake!

---

## 🛠️ How to Do Everything (No Coding Required!)

*💡 Pro-Tip: Download [GitHub Desktop](https://desktop.github.com/) **OR** [VSCode Desktop](https://code.visualstudio.com/). It lets you do everything below by clicking buttons instead of typing scary terminal commands!*

### 1️⃣ Creating a New Project (Repo)
1. Click the green **"New"** button at the top right of the organization page.
2. **Name** your project (e.g., `hpu-dashboard`).
3. Check the box to add a **README file**.
4. Click **Create repository**. Done!

### 2️⃣ Keeping Things Secret (Private Repos)
Because we handle government and health data, most of our work must be hidden from the public.
* When creating a new project, simply select **"Private"** instead of "Public". 
* Only invited HPU team members will even know this folder exists.

### 3️⃣ Syncing Work (Push & Pull)
If you are using the **GitHub Desktop App**:
* **Pull (Get latest work):** Click the **"Fetch Origin"** button at the top. This downloads any changes your teammates made while you were asleep.
* **Push (Share your work):** Made a change? Type a quick summary in the bottom left box, click **"Commit to main"** (Save), then click **"Push to origin"** (Upload).

### 4️⃣ The Time Machine (Backup & Revert)
The beauty of GitHub is that you cannot permanently break anything. Every time you Push (upload), GitHub saves a permanent backup.
1. Open GitHub Desktop and click the **"History"** tab.
2. You will see a list of every time anyone clicked "Save".
3. Right-click the snapshot from *before* things broke, and click **"Revert commit"**. 
4. The file magically reappears.

### 5️⃣ Managing the Team & Access
We use **Teams** to keep things organized. 
1. Go to the **Teams** tab at the top of the HPU Organization page.
2. Here, you will see groups like *Dashboard Admins*, *Data Analysts*, or *Pembangunan Team*.
3. **To give someone access:** Add them to a Team, and they automatically get access to all the private project folders that Team owns. 

---

### 💻 VS Code "Cheat Sheet" (For Developers)
Most of us use Visual Studio Code (VS Code). You can do everything by clicking the Source Control icon (the branch symbol on the left menu), but if you prefer the terminal, here are the only 4 commands you use 95% of the time:

# 1. Download a project to your laptop (Only do this once)
git clone https://github.com/health-performance-unit/your-project.git

# 2. Get the newest updates from your team (Do this every morning!)
git pull

# 3. Save your work (Take a snapshot)
git add .
git commit -m "Updated the login screen colors"

# 4. Upload your saved work to the HPU Cloud (Do this every evening!)
git push

---

### 🆘 Need Help?
If you are ever afraid of breaking the live project, just ask the Admin to help you create a **"Branch"**—a completely safe, invisible sandbox copy of the project where you can experiment without touching the real thing!
