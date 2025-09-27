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

<img width="1919" height="1019" alt="Screenshot 2025-09-26 190624" src="https://github.com/user-attachments/assets/0c2f3356-8e31-421c-a849-4cf8f31051c0" />

<img width="1918" height="1025" alt="Screenshot 2025-09-26 190657" src="https://github.com/user-attachments/assets/feb82020-4c03-44f2-bd09-8f95a2266592" />

<img width="1919" height="1024" alt="Screenshot 2025-09-26 190814" src="https://github.com/user-attachments/assets/7a6f52f1-8d45-44bc-9fcc-a7ebc37f3677" />

<img width="1919" height="1016" alt="Screenshot 2025-09-26 190826" src="https://github.com/user-attachments/assets/504da8df-1f35-492d-bab9-233d592006eb" />




🖼️ Screenshots

<img width="1919" height="557" alt="Screenshot 2025-09-26 182048" src="https://github.com/user-attachments/assets/c6b92b14-4423-48e9-b593-e49579c43b3e" />

<img width="1919" height="966" alt="Screenshot 2025-09-26 182223" src="https://github.com/user-attachments/assets/dc99e0d6-876b-41de-9ef7-205f78e96017" />

<img width="1919" height="970" alt="Screenshot 2025-09-26 182240" src="https://github.com/user-attachments/assets/ab8c617e-d964-4b46-b894-a8f63dddcdcd" />

<img width="1919" height="980" alt="Screenshot 2025-09-26 182939" src="https://github.com/user-attachments/assets/3823482f-78c1-4a38-a258-0081d5cebd9a" />

<img width="1919" height="966" alt="Screenshot 2025-09-26 183152" src="https://github.com/user-attachments/assets/ffc4d41d-21a0-4f92-ba5e-77f7f0acf3df" />

<img width="1918" height="962" alt="Screenshot 2025-09-26 183202" src="https://github.com/user-attachments/assets/3a55ac6f-d7a3-476e-a018-147a17236719" />



🏷️ Versioning

Current stable release: v1.0

Future releases will be tagged as vX.Y
