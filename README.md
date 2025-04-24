# Student Mockups Repository

Welcome! This repository is for submitting group presentations for **[Intelligent Learning Environments - Lab]**.

Each group should:
- Create a **new branch** for your submission.
- Add your mockups in a folder named after your group.
- Submit a **Pull Request (PR)** to merge it into `main`.

---

### Submission Instructions

Step 1: Clone the repo
```sh
git clone https://github.com/COLAPS-Research/ILE-Lab-Mockups.git
cd ILE-Lab-Mockups
```

Step 2: Create a branch for your group (replace GROUP_NUMBER with your actual group name)
```sh
git checkout -b GROUP_NUMBER
```

Step 3: Add your folder and presentation
```sh
mkdir GROUP_NUMBER
```
Add your mockups (e.g., submodule repo, .txt, .pdf, .pptx, etc.) inside this folder

Step 4: Stage and commit your changes
```sh
git add GROUP_NUMBER
git commit -m "Add presentation for GROUP_NUMBER"
```

Step 5: Push your branch
```sh
git push -u origin GROUP_NUMBER
```


## Structure
📁 student-presentations/
│
├── README.md
├── Group1_Name/
│   ├── submodule, .txt, .pdf, .pptx, etc.
│   ├── others/
│
├── Group2_Name/
│   ├── submodule, .txt, .pdf, .pptx, etc.
│   ├── others/
│
├── Group3_Name/
│   ├── submodule, .txt, .pdf, .pptx, etc.
│   ├── others/
|
└── .gitignore

