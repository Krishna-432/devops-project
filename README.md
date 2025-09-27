# DevOps Project with Git

This project demonstrates **version control best practices** using Git and GitHub.  
It simulates a real-world DevOps workflow with proper branching, pull requests, tagging, and documentation.

---
---

## 📂 Project Structure

devops-project/
│── README.md # Project overview
│── .gitignore # Ignored files
│── docs/ 
│ └── tasks.md # Step-by-step documentation
│── src/
│ └── app.py # Example application code
│── scripts/
│ └── deploy.sh # Example deployment script

---

## 🌳 Branching Strategy

We follow a **Git Feature Branch Workflow**:

- **main** → Production-ready, stable branch  
- **dev** → Integration branch (all tested features are merged here first)  
- **feature-\*** → Short-lived branches for individual features  

Flow:


feature-* → dev → main


---

## 🔄 Workflow

1. **Initialize repo** → Git + GitHub setup  
2. **Create branches** → main, dev, feature-*  
3. **Develop features** → Work inside `feature-*` branches  
4. **Pull Request (PR)** → Merge `feature-*` → `dev`  
5. **Release** → Merge `dev` → `main`  
6. **Tag versions** → e.g., `v1.0`  

---

## 🛠️ Tools Used

- **Git** → Version control  
- **GitHub** → Remote repo, pull requests, tagging  
- **Markdown** → Documentation (`README.md`, `tasks.md`)  

---

## 📖 Documentation

Detailed progress logs for each step are documented in:  
👉 [docs/tasks.md](docs/tasks.md)

---

## 🎉 Outcomes

- ✅ Repo initialized and live on GitHub  
- ✅ Proper branching strategy (`main`, `dev`, `feature-*`)  
- ✅ Pull requests used for clean merges  
- ✅ `.gitignore`, `README.md`, and documentation added  
- ✅ Release tagged (`v1.0`)  

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/<username>/devops-project.git
   cd devops-project


Run the example app:

python src/app.py


Run the deployment script (Linux/macOS):

./scripts/deploy.sh


(Windows users can run it inside Git Bash or WSL.)

Commands Used  


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b7a28957-04fb-4f64-bb2f-a99215719837" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/26b49ddc-c999-49c2-8863-7df90a698838" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dfae09cd-7097-4216-a883-ae1b430668f7" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/49336f9d-613b-4530-86fa-c3c71f8bc0e6" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fee2a8a0-c15c-433d-a041-8fc0b7660e9b" />











🏷️ Versioning

Current stable release: v1.0

Future releases will be tagged as vX.Y
