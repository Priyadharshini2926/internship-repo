# internship-repo
🔍 What is OCR?
OCR (Optical Character Recognition) is a technology used to extract text from scanned documents, images, or PDFs and convert them into editable/searchable text.

🧠 OCR Working Process
Image Preprocessing – noise removal, grayscale, deskewing, contrast.

Text Detection – locating text regions.

Character Recognition – recognizing characters/words.

Post-processing – correcting recognition errors using dictionaries/language models.

⚠️ OCR Challenges
Blurred or low-quality images

Handwriting recognition

Mathematical symbols

Mixed content (text + diagrams)

Complex layouts

📝 Types of Answer Sheets Explored
Theory-Based – paragraph-style handwritten answers.

Mathematical – equations, symbols (∫, π), derivations.

Diagram-Based – biology, circuits, labeled figures.

Mixed Content – combinations of text, math, and diagrams.

🧪 Tools and Solutions
Tesseract OCR, Google Cloud Vision, Microsoft Azure OCR

For Math: MathPix, InftyReader

For diagrams: Combine OpenCV + Tesseract

For complex layouts: LayoutParser, Detectron2, DocTR
🔹 What is Git?
Git is a Distributed Version Control System (DVCS) used to track changes in source code. It allows multiple developers to collaborate without overwriting each other's work.

✅ Git Features
Distributed architecture

SHA-1 data integrity

Fast branching & merging

Local commit history

Collaborative development support

🔧 Common Git Commands
# Configuration
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"

# Repo Setup
git init
git clone <repo_url>

# Staging & Committing
git add .
git commit -m "Message"

# Branching
git branch
git checkout <branch_name>
git merge <branch_name>

# Syncing
git push origin <branch>
git pull

# Logs and Undo
git log
git reset <file>
🔹 What is GitHub?
GitHub is a web-based platform built on top of Git. It allows code hosting, collaboration, and project management with features like Pull Requests, Issues, and Actions (CI/CD).

🔑 Key GitHub Concepts
Term	Description
Repo	Project folder with code
Fork	Personal copy of a repo
Pull Request	Propose changes
Issue	Bug/task tracking
README	Introductory markdown file
