<!--
author:   Your Name
email:    your.email@example.com
version:  1.0.0
language: en
narrator: US English Female

comment:  Offline AI Course Designing - A beginner-friendly guide for creating academic courses using AI without internet

icon: https://liascript.github.io/img/logo.png

-->

# 📘 Workflow Guide_BMAD setup for offline implementation

**Beginner Step-by-Step Student Guide**  
*(Low Digital Skills + Low RAM)*

## 🎯 Course Overview

    --{{0}}--
Welcome! In this interactive training, you will learn how to design a complete academic course using Artificial Intelligence without internet, By the end of this course, you'll be able to create course materials automatically using free, offline tools on your own computer

**By the end of this course, you will be able to:**

- [x] Design a complete academic course structure
- [x] Use AI tools offline on low-spec laptops
- [x] Create course materials automatically
- [x] Develop learning activities and assessments
- [x] Build a teaching personality profile

**No programming experience required!** ⚠️

---

## 🖥️ Pre-Course Check: Computer Requirements

Before we begin, verify your computer meets the minimum requirements:

| Item | Requirement |
|------|------------|
| Operating System | Windows 10 or Windows 11 |
| RAM | At least 4 GB (8 GB is better) |
| Storage | At least 10 GB free space |
| Internet | Needed **only once** for installation |

> **Important:** After initial setup, NO INTERNET is required!

---

## 🧩 Module 1: Understanding the Tools

    --{{0}}--
Before we start installing anything, it's important to understand what each tool does and how they work together, Think of this like learning about the ingredients before you start cooking, This section is very important - it builds your foundation

      {{0}}
This section is **VERY IMPORTANT** - it builds your foundation!

**How All The Tools Work Together:**

```ascii
        ┌─────────────────────────────────┐
        │         YOUR COMPUTER           │
        │                                 │
        │  ┌──────────┐    ┌──────────┐  │
        │  │ VS Code  │───→│  Python  │  │
        │  │(Editor)  │    │(Control) │  │
        │  └──────────┘    └─────┬────┘  │
        │                        │        │
        │                        ▼        │
        │                  ┌──────────┐  │
        │                  │  Ollama  │  │
        │                  │ (Engine) │  │
        │                  └─────┬────┘  │
        │                        │        │
        │                        ▼        │
        │                  ┌──────────┐  │
        │                  │DeepSeek  │  │
        │                  │(AI Brain)│  │
        │                  └──────────┘  │
        │                                 │
        └─────────────────────────────────┘
                NO INTERNET NEEDED!
```

    --{{1}}--
What this diagram shows is how all four tools work together on your computer, VS Code is where you write and see your work, Python controls everything automatically. Ollama is the engine that runs the AI, And DeepSeek is the actual AI brain that creates your course content, The best part? No internet is needed after the initial setup!

      {{1}}
**What this means:**
- **VS Code** = Where you write and see your work
- **Python** = Controls everything automatically
- **Ollama** = Runs the AI on your computer
- **DeepSeek** = The actual AI that creates content

---

### 1.1 What is Python?

    --{{0}}--
Python is a simple programming language that allows us to automate tasks, communicate with AI models, and create files automatically, Think of Python as the remote control for our AI system.

      {{0}}
Python is a simple programming language that allows us to:

- Automate repetitive tasks
- Communicate with AI models
- Create files automatically

> 💡 **Think of it this way:** We use Python to **control** the AI, not to do complex mathematics or programming.

---

### 1.2 What is Ollama?

    --{{0}}--
Ollama is a program that runs AI models on your own computer, It does not send data to the internet and works completely offline, Think of Ollama as a box that contains AI inside your laptop - everything stays local and private

      {{0}}
**Ollama** is a program that:

- ✅ Runs AI models on **your own computer**
- ✅ Does **not** send data to the internet
- ✅ Works completely **offline**

> 💡 **Analogy:** Think of Ollama as a **box that contains AI inside your laptop** - everything stays local and private.

```ascii
┌─────────────────────────────┐
│    YOUR LAPTOP              │
│  ┌─────────────────────┐   │
│  │   OLLAMA (Box)      │   │
│  │  ┌───────────────┐  │   │
│  │  │  AI Brain     │  │   │
│  │  │  (DeepSeek)   │  │   │
│  │  └───────────────┘  │   │
│  └─────────────────────┘   │
└─────────────────────────────┘
     NO INTERNET NEEDED!
```

---

### 1.3 What is DeepSeek?

    --{{0}}--
DeepSeek is the AI brain that generates course content and text, designs course structures, creates learning activities, and works completely offline, We use DeepSeek one-point-five-B because it is safe for low RAM computers, stable, and perfect for learning

      {{0}}
**DeepSeek** is the **AI brain** that:

- Generates course content and text
- Designs course structures
- Creates learning activities
- Works completely offline

**We use DeepSeek 1.5B** because it is:

- ✅ Safe for low RAM (4-8GB)
- ✅ Slower, but very stable
- ✅ Perfect for learning

> **Remember:**
> - **Ollama** = Container/Engine that runs AI
> - **Python** = Programming tool that controls the process
> - **DeepSeek** = AI brain that generates content

---

### 1.4 What is VS Code?

    --{{0}}--
VS Code, or Visual Studio Code, is a free code editor from Microsoft, It makes it easy to write and run Python scripts, has a built-in terminal so you don't need a separate PowerShell window, and is user-friendly with color coding and suggestions, We'll use VS Code to write and run our AI automation script - it's much easier than using PowerShell alone!

      {{0}}
**VS Code (Visual Studio Code)** is:

- A free code editor from Microsoft
- Makes it easy to write and run Python scripts
- Has a built-in terminal (no need for separate PowerShell)
- User-friendly with color coding and suggestions

> **We'll use VS Code** to write and run our AI automation script - it's much easier than using PowerShell alone!

```
┌─────────────────────────────┐
│     VS CODE WINDOW          │
│  ┌─────────────────────┐   │
│  │  Your Python Code   │   │
│  │                     │   │
│  └─────────────────────┘   │
│  ┌─────────────────────┐   │
│  │  Terminal (below)   │   │
│  │  Run code here ▶    │   │
│  └─────────────────────┘   │
└─────────────────────────────┘
```

---

## 🛠️ Module 2: Installation Process

    --{{0}}--
Now we're ready to install all the tools we need, This is a one-time-only process,After this initial setup, everything will work completely offline without any internet connection

      {{0}}
**ONE TIME ONLY** - After this, everything works offline!

### STEP 1: Install VS Code (RECOMMENDED!)

#### 2.0 Download and Install VS Code

**Step-by-step:**

1. Open web browser
2. Go to: [https://code.visualstudio.com](https://code.visualstudio.com)
3. Click **Download for Windows**
4. Run the installer
5. Keep all default settings and click **Next** → **Install**

#### 2.0.1 Verify VS Code Installation

**Open VS Code:**

1. Press **Windows key**
2. Type: `VS Code` or `Visual Studio Code`
3. Press **Enter**

✅ If VS Code opens, you're ready!

**✓ Visual Checkpoint - Does your screen look like this?**

```
┌─────────────────────────────────────────┐
│ Visual Studio Code                      │
│ File  Edit  View  ...                   │
├─────────────────────────────────────────┤
│                                         │
│   Welcome to VS Code!                   │
│                                         │
│   Start                                 │
│   • New file                            │
│   • Open folder                         │
│                                         │
└─────────────────────────────────────────┘
```

If YES → Continue to next step ✅  
If NO → Ask your instructor for help 🆘

---

### STEP 2: Install Python (CRITICAL!)

#### 2.1 Which Python Version?

- ✅ **Python 3.11 (64-bit)** ← Install this!
- ❌ **NOT Python 3.13** or experimental versions

#### 2.2 Installation Instructions

**Step-by-step:**

1. Open web browser
2. Go to: [https://www.python.org](https://www.python.org)
3. Click **Downloads**
4. Download **Python 3.11.x (64-bit)**

#### 2.3 CRITICAL Installation Settings

    --{{0}}--
This is the most important step in the entire installation process, When the Python installer window opens, you must check a specific box, or Python will not work from VS Code, Pay very close attention to this step

      {{0}}
> **⚠️ MOST IMPORTANT STEP!**

When the installer window opens:

      {{1}}
```
┌────────────────────────────────────┐
│ Install Python 3.11                │
│                                    │
│ ☑ Add Python to PATH  ← CHECK THIS│
│                                    │
│        [Install Now]               │
└────────────────────────────────────┘
```

    --{{2}}--
You must check the box that says "Add Python to PATH", This tells Windows where to find Python when you type commands, Without this, nothing will work

      {{2}}
**You MUST check** ☑ Add Python to PATH

    --{{3}}--
After you check the box, click the Install Now button and wait for the installation to complete

      {{3}}
Then click: **Install Now**

---

#### 2.4 Verify Python Installation

**Open VS Code Terminal:**

1. Open **VS Code**
2. Click **Terminal** menu → **New Terminal** (or press Ctrl + `)
3. A terminal panel opens at the bottom

**Type this command in the terminal:**

```bash
py --version
```

**Expected result:**

```
Python 3.11.x
```

> ✅ If you see the version number, Python is installed correctly!

**✓ Visual Checkpoint - Does your terminal look like this?**

```
PS C:\Users\Public\CourseProjectTool> py --version
Python 3.11.9
PS C:\Users\Public\CourseProjectTool> _
```

**Verification Checklist:**

- [ ] I see "Python 3.11" in the terminal
- [ ] The version number appears (like 3.11.9)
- [ ] No error message saying "not recognized"

**If you see an error** → Go to [Troubleshooting Section](#troubleshooting-common-problems) 🆘

---

### STEP 3: Install Ollama

#### 2.5 Ollama Installation

**Step-by-step:**

1. Go to: [https://ollama.com](https://ollama.com)
2. Click **Download**
3. Choose **Windows**
4. Install normally: Next → Next → Finish

#### 2.6 Verify Ollama Installation

**In VS Code Terminal, type:**

```bash
ollama --version
```

**Expected result:**

```
ollama version 0.xx.x
```

> ✅ If you see a version number, Ollama is working!

**✓ Visual Checkpoint:**

```
PS C:\Users\Public\CourseProjectTool> ollama --version
ollama version 0.4.0
PS C:\Users\Public\CourseProjectTool> _
```

**Verification Checklist:**

- [ ] I see "ollama version" followed by numbers
- [ ] No error message appears
- [ ] I can see the Ollama icon in my system tray (bottom-right corner of screen)

**If you see an error** → Go to [Troubleshooting Section](#troubleshooting-common-problems) 🆘

---

### STEP 4: Download the AI Model

> ⚠️ This step requires **internet only once**

#### 2.7 Pull DeepSeek Model

**In VS Code Terminal, type:**

```bash
ollama pull deepseek-r1:1.5b
```

⏳ **Wait 5–15 minutes** (depends on your internet speed)

You'll see a progress bar:

```
pulling manifest
pulling 4b8f7d8... 100%
verifying sha256 digest
success
```

---

#### 2.8 Test the AI

**Type this command in VS Code Terminal:**

```bash
ollama run deepseek-r1:1.5b
```

**You should see:**

```
>>> Send a message
```

**Type:** `Hello`

**If AI replies** → ✅ **Success!**

**To exit, type:** `/bye`

**✓ Visual Checkpoint - Complete AI Test:**

```
PS C:\Users\Public\CourseProjectTool> ollama run deepseek-r1:1.5b
>>> Send a message (/? for help)

>>> Hello
<think>
The user greeted me, I should respond politely
</think>

Hello! How can I help you today?

>>> /bye
PS C:\Users\Public\CourseProjectTool> _
```

**What you should see:**

1. **First:** `>>> Send a message` appears
2. **You type:** `Hello` and press Enter
3. **You might see:** `<think>` tags (this is normal - AI is thinking!)
4. **Then:** AI responds with a greeting
5. **To exit:** Type `/bye` and press Enter

**Important Notes:**

- ⏳ **First response may take 10-30 seconds** (especially on low-RAM computers)
- 💭 **Screen might look frozen** - this is NORMAL, just wait!
- 🤔 **`<think>` tags** - These show AI's reasoning process (you can ignore them)

**Verification Checklist:**

- [ ] I typed `Hello` and got a response
- [ ] I successfully exited with `/bye`
- [ ] AI model is working

**If AI doesn't respond or you see errors** → Go to [Troubleshooting Section](#troubleshooting-common-problems) 🆘

---

## 📁 Module 3: Creating Course Folders

**No AI needed yet** - Just organizing your workspace!

### STEP 5: Create Project Folder Structure

#### 3.1 Navigate to Public Folder

**Steps:**

1. Open **File Explorer** (Windows + E)
2. Navigate to: `C:\Users\Public`
3. Right-click → **New** → **Folder**
4. Name it: `Course_Project`

#### 3.2 Create Subfolders

    --{{0}}--
Inside the Course Project folder, we need to create four subfolders, These folders will hold different parts of your course: personality information, course structure, learning activities, and final output files

      {{0}}
**Inside Course_Project, create these folders:**

      {{1}}
```
Course_Project/
├── personality/
├── structure/
├── activities/
└── output/
```

    --{{2}}--
Here's how to create each folder, Open the Course Project folder, right-click in the empty space, select New, then Folder, and rename it to match the names shown above, Repeat this four times to create all four folders

      {{2}}
**How to create each:**

1. Open `Course_Project`
2. Right-click → **New** → **Folder**
3. Rename to each name above

**✓ Visual Checkpoint - Does your folder look like this?**

```
📁 Course_Project
   ├── 📁 personality
   ├── 📁 structure
   ├── 📁 activities
   └── 📁 output
```

**Verification Checklist:**

- [ ] I have created 4 folders
- [ ] All folders are inside Course_Project
- [ ] Folder names match exactly (personality, structure, activities, output)

**Tip:** Make sure spelling is exact - "activities" not "activity"!

---

## 🤖 Module 4: AI Automation Setup

### STEP 6: Open Project in VS Code

#### 4.1 Open Folder in VS Code

**Steps:**

1. Open **VS Code**
2. Click **File** → **Open Folder**
3. Navigate to: `C:\Users\Public`
4. Select `CourseProjectTool` folder (create it if it doesn't exist)
5. Click **Select Folder**

> ✅ You should now see `CourseProjectTool` in the VS Code Explorer panel on the left

**✓ Visual Checkpoint - Does VS Code look like this?**

```
┌─────────────────────────────────────────┐
│ VS Code - CourseProjectTool             │
├──────────┬──────────────────────────────┤
│ EXPLORER │                              │
│          │                              │
│ 📁 COURSE│  (Empty workspace area)      │
│ PROJECTT │                              │
│ OOL      │                              │
│          │                              │
│ (empty)  │                              │
│          │                              │
└──────────┴──────────────────────────────┘
```

**Verification Checklist:**

- [ ] Left panel shows "COURSEPROJECTTOOL" at the top
- [ ] The folder icon is visible
- [ ] Main area is empty (no files yet)

**If you don't see the folder** → Click **File** → **Open Folder** and try again 🆘

---

### STEP 7: Create AI Automation Script

#### 4.2 Create Python Script in VS Code

**In VS Code:**

1. Click on **New File** icon (or File → New File)
2. Save it immediately: **File** → **Save As**
3. Navigate to `C:\Users\Public\CourseProjectTool`
4. Name it: `ai_course_designer.py`
5. Click **Save**

> ✅ You should now see `ai_course_designer.py` in the Explorer panel

**✓ Visual Checkpoint - Does VS Code look like this?**

```
┌─────────────────────────────────────────┐
│ VS Code - ai_course_designer.py         │
├──────────┬──────────────────────────────┤
│ EXPLORER │  (Cursor blinking here)      │
│          │                              │
│ 📁 COURSE│                              │
│ PROJECTT │                              │
│ OOL      │                              │
│  📄 ai_c │                              │
│    ourse │                              │
│    _desi │                              │
│    gner. │                              │
│    py    │                              │
└──────────┴──────────────────────────────┘
```

**Verification Checklist:**

- [ ] File `ai_course_designer.py` appears in the left panel
- [ ] File has a Python icon (🐍) or document icon
- [ ] Main area is empty and ready for code

**Now you're ready to paste the code!**

---

#### 4.3 Complete Python Code (LOW-RAM SAFE)

**In VS Code, paste this FULL code into ai_course_designer.py:**

```python
import subprocess
from pathlib import Path

# Project directory where course files will be saved
PROJECT_DIR = Path(r"C:\Users\Public\Course_Project")
MODEL = "deepseek-r1:1.5b"

def ask_ai(prompt):
    """Send a prompt to the AI and get response"""
    result = subprocess.run(
        ["ollama", "run", MODEL],
        input=prompt,
        text=True,
        capture_output=True
    )
    return result.stdout.strip()

def write_file(path, text):
    """Write AI-generated content to file"""
    path.parent.mkdir(parents=True, exist_ok=True)
    path.write_text(text, encoding="utf-8")

def main():
    print("🤖 Starting Offline AI Course Generator...")
    print("⏳ This may take 30-90 seconds on low-RAM systems...\n")
    
    # Generate personality profile
    print("📝 Creating teacher personality...")
    write_file(
        PROJECT_DIR / "personality" / "personality.yaml",
        ask_ai("Create YAML for teacher personality and student profile.")
    )
    
    # Generate course structure
    print("📚 Creating course structure...")
    write_file(
        PROJECT_DIR / "structure" / "structure.yaml",
        ask_ai("Create YAML for a 6-week offline course structure.")
    )
    
    # Generate learning activities
    print("🎯 Creating learning activities...")
    write_file(
        PROJECT_DIR / "activities" / "activities.yaml",
        ask_ai("Create YAML for weekly offline learning activities.")
    )
    
    # Generate assessment criteria
    print("✅ Creating assessment criteria...")
    write_file(
        PROJECT_DIR / "output" / "assessment.md",
        ask_ai("Create Markdown assessment criteria for the course.")
    )
    
    print("\n🎉 Offline AI course created successfully!")
    print(f"📁 Check your files in: {PROJECT_DIR}")

if __name__ == "__main__":
    main()
```

**Save the file** (Ctrl + S)

---

## ▶️ Module 5: Running Your AI Course Generator

### STEP 8: Execute the Script in VS Code

#### 5.1 Open Terminal in VS Code

**If terminal is not already open:**

1. In VS Code, click **Terminal** menu
2. Select **New Terminal**
3. Terminal panel appears at the bottom

#### 5.2 Navigate to Your Script

The terminal should already be in the `CourseProjectTool` folder. If not, type:

```bash
cd C:\Users\Public\CourseProjectTool
```

Press **Enter**

#### 5.3 Run the Python Script

    --{{0}}--
Now comes the moment of truth, We're going to run the script that will automatically generate your course materials, This will take some time, so let me explain what to expect,

      {{0}}
**Type:**

```bash
py ai_course_designer.py
```

Press **Enter**

    --{{1}}--
After you press Enter, you'll need to wait, On low-RAM systems, this typically takes thirty to ninety seconds total, The screen may look frozen between steps - this is completely normal, Do not close the window!

      {{1}}
⏳ **WAIT 30–90 seconds**

> Low-RAM systems are slower - **this is completely normal!**

    --{{2}}--
Here's exactly what you'll see while the script is running, The script will display progress messages with emoji symbols, Each step takes fifteen to thirty seconds, and the screen may look frozen between each emoji, The total time is usually one to two minutes, sometimes up to three minutes on very slow computers

      {{2}}
**✓ Visual Checkpoint - What you'll see while running:**

```
PS C:\Users\Public\CourseProjectTool> py ai_course_designer.py
🤖 Starting Offline AI Course Generator...
⏳ This may take 30-90 seconds on low-RAM systems...

📝 Creating teacher personality...
(WAIT - screen may look frozen for 15-30 seconds)

📚 Creating course structure...
(WAIT - screen may look frozen for 15-30 seconds)

🎯 Creating learning activities...
(WAIT - screen may look frozen for 15-30 seconds)

✅ Creating assessment criteria...
(WAIT - screen may look frozen for 15-30 seconds)

🎉 Offline AI course created successfully!
📁 Check your files in: C:\Users\Public\Course_Project
PS C:\Users\Public\CourseProjectTool> _
```



**If script stops, freezes, or shows error messages** → Go to [Troubleshooting Section](#troubleshooting-common-problems) 🆘

---

### STEP 9: Verify Your Results

#### 5.4 Check Generated Files

**Navigate to:**

```
C:\Users\Public\Course_Project
```

**You should now see these files:**

- ✅ `personality/personality.yaml`
- ✅ `structure/structure.yaml`
- ✅ `activities/activities.yaml`
- ✅ `output/assessment.md`

**✓ Visual Checkpoint - Does File Explorer look like this?**

```
📁 Course_Project
   ├── 📁 personality
   │      └── 📄 personality.yaml
   ├── 📁 structure
   │      └── 📄 structure.yaml
   ├── 📁 activities
   │      └── 📄 activities.yaml
   └── 📁 output
          └── 📄 assessment.md
```

**Verification Checklist:**

- [ ] I see 4 folders (personality, structure, activities, output)
- [ ] Each folder has 1 file inside it
- [ ] All file names end with `.yaml` or `.md`
- [ ] Files are NOT empty (right-click → Properties → Size is more than 0 KB)

**If files are missing or empty** → Go to [Troubleshooting Section](#troubleshooting-common-problems) 🆘

---

#### 5.5 Review Generated Content

**You can open and review files directly in VS Code:**

1. In VS Code: **File** → **Open Folder**
2. Select `C:\Users\Public\Course_Project`
3. Click through each folder and file to review:
   - **personality.yaml** - Teaching style and student profile
   - **structure.yaml** - 6-week course outline
   - **activities.yaml** - Weekly learning activities
   - **assessment.md** - Assessment criteria

**Or** open each file with Notepad by navigating in File Explorer.

---

### 💡 How to Customize Your Course

**Want to modify your AI-generated course?**

1. In VS Code, open `ai_course_designer.py`
2. Find the prompt texts (inside the `ask_ai()` functions)
3. Modify them to customize your course:
   - Change "6-week" to "4-week" or "12-week"
   - Specify subject area: "for engineering students"
   - Add difficulty level: "beginner-friendly"
4. Save the file (Ctrl + S)
5. Run the script again in the terminal: `py ai_course_designer.py`

**Example customization:**

```python
# Original:
ask_ai("Create YAML for a 6-week offline course structure.")

# Modified:
ask_ai("Create YAML for a 4-week beginner course structure for engineering students.")
```

---

## 🔧 Troubleshooting Common Problems



**Troubleshooting Flow:**

```ascii
   ┌─────────────────┐
   │ Having a       │
   │ Problem?        │
   └────────┬────────┘
            │
            ▼
   ┌─────────────────┐
   │ Find your       │
   │ error message   │
   └────────┬────────┘
            │
            ▼
   ┌─────────────────┐
   │ Try the         │
   │ solution        │
   └────────┬────────┘
            │
      ┌─────┴─────┐
      │           │
      ▼           ▼
   Fixed!    Still broken?
      │           │
      │           ▼
      │    ┌─────────────┐
      │    │ Try next    │
      │    │ solution or │
      │    │ ask teacher │
      │    └─────────────┘
      │
      ▼
   Continue
   training!
```

---

### Problem 1: "py is not recognized" Error

**What you see:**

```
'py' is not recognized as an internal or external command
```

**What this means:** Python was not added to PATH during installation.

**Solution:**

1. **Uninstall Python:**
   - Press Windows key → Type "Add or remove programs"
   - Find "Python 3.11" → Click **Uninstall**

2. **Reinstall Python:**
   - Go back to [STEP 2](#step-2-install-python-critical)
   - **THIS TIME:** Make sure to check ☑ "Add Python to PATH" box
   - Install again

3. **Verify:**
   - Close and reopen VS Code
   - Open new terminal
   - Type: `py --version`

---

### Problem 2: "ollama: command not found"

**What this means:** Ollama is not installed or not running.

**Solution:**

1. **Check if Ollama is installed:**
   - Look in system tray (bottom-right corner)
   - Do you see an Ollama icon? (looks like a llama)

2. **If NO icon:**
   - Reinstall Ollama: Go to [STEP 3](#step-3-install-ollama)

3. **If YES icon:**
   - Right-click the Ollama icon
   - Click "Restart Ollama"
   - Wait 10 seconds
   - Try your command again

---

### Problem 3: AI Model Not Responding / Connection Refused

**What you see:**

```
Error: could not connect to ollama app, is it running?
```

**Solution:**

1. **Check Ollama is running:**
   - Look for Ollama icon in system tray
   - If missing → Open Start Menu → Type "Ollama" → Click to start

2. **Restart Ollama:**
   - Right-click Ollama icon in system tray
   - Click "Quit Ollama"
   - Wait 5 seconds
   - Open Start Menu → Type "Ollama" → Click to start
   - Wait 10 seconds

3. **Test again:**
   ```bash
   ollama run deepseek-r1:1.5b
   ```

---

### Problem 4: Script Runs But No Files Created

**What to check:**

1. **Did the script finish?**
   - You should see: "🎉 Offline AI course created successfully!"
   - If you DON'T see this → The script crashed

2. **Check folders exist:**
   - Go to `C:\Users\Public\Course_Project`
   - Are the 4 folders there? (personality, structure, activities, output)
   - If NO → Go back to [STEP 5](#step-5-create-project-folder-structure)

3. **Check Ollama is running:**
   - See Problem 3 above

4. **Check Python script path:**
   - Open `ai_course_designer.py`
   - Look at line: `PROJECT_DIR = Path(r"C:\Users\Public\Course_Project")`
   - Make sure path matches where you created folders

---

### Problem 5: Script Takes Forever / Seems Frozen

**Is this normal?**

- ✅ **NORMAL:** Each step takes 15-30 seconds on low-RAM computers
- ✅ **NORMAL:** Total time 1-3 minutes
- ✅ **NORMAL:** Screen looks frozen between emoji messages
- ❌ **NOT NORMAL:** More than 5 minutes with no new messages

**What to do if stuck more than 5 minutes:**

1. **Press Ctrl + C** to stop the script
2. **Check Ollama is running** (see Problem 3)
3. **Close other programs** to free up RAM:
   - Close web browser
   - Close unnecessary applications
4. **Try again:** `py ai_course_designer.py`

---

### Problem 6: Error Messages with File Paths

**What you see:**

```
FileNotFoundError: [Errno 2] No such file or directory
```

**Solution:**

1. **Check folder spelling exactly:**
   - It must be `Course_Project` not `course_project` or `CourseProject`
   - It must be `personality` not `Personality`

2. **Make sure folders exist:**
   - Go to `C:\Users\Public\`
   - Verify all folders are created

3. **Check your script:**
   - Line should say: `PROJECT_DIR = Path(r"C:\Users\Public\Course_Project")`
   - Make sure the `r` is there before the quotes

---

### Problem 7: Files Are Empty (0 KB)

**What this means:** AI didn't generate content.

**Solution:**

1. **Check Ollama model is downloaded:**
   ```bash
   ollama list
   ```
   - You should see `deepseek-r1:1.5b` in the list

2. **If NOT in list:**
   ```bash
   ollama pull deepseek-r1:1.5b
   ```
   - Wait for download to complete

3. **Test AI manually:**
   ```bash
   ollama run deepseek-r1:1.5b
   ```
   - Type: `Hello`
   - Does it respond? If NO → See Problem 3

4. **Delete empty files and run script again**

---

### Problem 8: "Permission Denied" Error

**Solution:**

1. **Run VS Code as Administrator:**
   - Close VS Code
   - Right-click VS Code icon
   - Click "Run as administrator"
   - Try again

2. **Or use different folder:**
   - Change script to use: `C:\Temp\Course_Project`
   - Create folders there instead

---

### Problem 9: Can't Find Terminal in VS Code

**Solution:**

1. **Open terminal:**
   - Click **Terminal** menu at top
   - Click **New Terminal**
   - OR press: `Ctrl + ` (Ctrl + backtick)

2. **If still no terminal:**
   - Close VS Code completely
   - Reopen VS Code
   - Try again

---

### Problem 10: YAML Files Look Strange When Opened

**This is normal!**

YAML files have special formatting:

```yaml
teacher:
  name: "Dr. Smith"
  style: "Interactive"
```

**What to do:**

- Don't worry about the format
- The AI generated this correctly
- You can read it, but don't need to edit it

---

### 🆘 Still Having Problems?

**Quick Diagnostics Checklist:**

Run these commands one by one and note any errors:

```bash
# 1. Check Python
py --version

# 2. Check Ollama
ollama --version

# 3. Check AI model
ollama list

# 4. Test AI
ollama run deepseek-r1:1.5b
```

Type `/bye` to exit AI test.

**If ALL these work:**
- Your installation is correct
- The problem is likely in the Python script or folder paths
- Double-check folder names and script carefully

**If ANY fail:**
- Note which one fails
- Go to the specific problem section above
- Follow the solution steps

**Need human help?**
- Ask your instructor
- Show them which command failed
- Show them the exact error message

---

### 🎯 Next Steps & Advanced Options

**You can now:**

- ✅ Modify prompts to generate different course types
- ✅ Create courses for different academic levels
- ✅ Experiment with different AI models
- ✅ Share this workflow with colleagues

**Want to go further?**

- Try creating a course for a different subject
- Experiment with longer course structures (12 weeks)
- Add more specific prompts for specialized content
- Combine multiple AI-generated courses

🎬 End of Course

**Thank you for participating in this training!**

Remember: AI is a tool to enhance your teaching, not replace your expertise.

**Happy Course Designing! 🚀**