
**Collaborative Portfolio Website Project Guide**

This guide will walk you through creating a collaborative portfolio website using Git and

GitHub. It covers project setup, Git/GitHub workflows, and project management.

**Objective**

Students will collaborate to build a portfolio website using HTML, CSS, and optionally

JavaScript. Each student will contribute to the project by adding their personalized sections,

practicing Git and GitHub workflows in a team environment.

**Steps**

**1. Setup the Project Repository**

**o**Create a new GitHub account for this project

**o**Create a private GitHub repository named **Collaborative-Portfolio**.

**o**Initialize the repository with:

**▪**A **README.md** describing the project.

**▪**A basic folder structure:

plaintext

Copy code

Collaborative-Portfolio/

├── index.html

├── styles/ │ └── main.css ├── assets/

└── README.md

**▪**An initial commit with the base structure.

**o**Set up the repository permissions (e.g., invite other members as collaborators).

**o**Clone the repository to your local machines.

**2. Define Project Roles**

**o**Assign roles to each team member:

**▪****Content Contributor:** Adds HTML content (e.g., About Me, Projects).

**▪****Designer:** Updates CSS for styling the sections.**▪****Reviewer:** Ensures content consistency and reviews Pull Requests.

**o**Create GitHub Issues to organize tasks:

**▪**Example: “Add an ‘About Me’ section,” “Design the Projects section,” or

“Improve site navigation.”

**o**Claim issues from the repository and assign yourselves.

**3. Branching Workflow**

**o**Git branching and naming conventions:

**▪**Use branch names like feature/about-section** or **fix/footer-

alignment**.**

**o**Create a new branch for their task:

git checkout -b feature/about-section

**o**Make changes locally, commit often with meaningful messages:

git add .

git commit -m "Add About Me section"

**4. Making a Pull Request**

**o**Push your branch to GitHub:

git push origin feature/about-section

**o**Create a Pull Request (PR) on the repository.

**o**Request reviews from peers or the assigned Reviewer.

**o**Review PRs for correctness and merge them after approval.

**5. Resolving Merge Conflicts**

**o**Pull changes from the main branch before merging:

git pull origin main

**o**Resolve conflicts, test changes, and push updates:

git add .

git push

git commit -m "Resolve merge conflict in index.html"**6. Project Completion**

**o**Guide students to polish the website:

**▪**Add a **CONTRIBUTORS.md** file listing team members.

**▪**Ensure all sections are well-styled and functional.

**▪**Deploy the project using GitHub Pages (Settings > Pages).

**o**Share the live URL with students for their portfolios.

**o**Verify your contributions appear correctly.

**o**Share feedback on the project experience.

**Milestones and Deliverables**

1.2.3.**Week 1:** Repository setup, branching, and initial content contributions.

**Week 2:** Adding styling and resolving merge conflicts.

**Week 3:** Finalizing and deploying the website.
