# NST Academic GitHub Repositories – Starter Guidelines

## 1. Purpose & Philosophy (Why)
We use GitHub to manage **content, curriculum, and academic documentation** in a collaborative, transparent, and version-controlled way.  
This ensures:
- **Centralized source of truth** for all academic material.
- **Version history** for curriculum, papers, and docs.
- **Collaboration** between faculty, staff, and students.
- **Quality & Consistency** through agreed repository standards.

---

## 2. Repository Naming Convention (What)
We organize repos into **Teams** based on subjects or domains.  

Format: `nst-acads-`

Examples:

- **nst-acads-dev** → Development courses team  
- **nst-acads-dsa** → Data Structures & Algorithms team  

Repos under these teams may include:

- `wap-sample-paper` – Sample papers for Web Application Programming.
- `curriculum` – Detailed curriculum & syllabus docs.

---

## 3. When to Create a Repository
Create a new repo when:
1. The content is **substantial** and has a clear standalone scope (e.g., course, subject, major resource).
2. Multiple contributors will work over time.
3. Version tracking will add value.
4. The repo needs **public sharing** or controlled collaboration.

Avoid creating a repo if:
- It’s a temporary or experimental file.
- It logically belongs in an **existing repo**.

---

## 4. Minimum Standards for Every Repository
Each repo **must** include:
1. **README.md**
   - Purpose of the repo
   - Scope (what’s inside)
   - Contribution guidelines
   - Contact person/owner
2. **Directory Structure**

/docs      → PDFs, DOCX, markdown docs
/media     → Images, diagrams
/archive   → Old versions

3. **LICENSE** (if intended for public sharing)
4. **CONTRIBUTING.md** (if multiple contributors)
5. **.gitignore** (to avoid committing unwanted files)

---

## 5. Management & Collaboration (How)
1. **Branching**
- `main` → Approved & stable version.
- Feature branches → Merge via Pull Requests (PRs).
2. **Pull Requests**
- At least one team review before merge.
3. **Versioning**
- Tag major updates: `v1.0`, `v2.0`, etc.
4. **Access Control**
- Teams manage write access.
5. **Documentation Updates**
- Update README.md if scope or structure changes.

---

## 6. Workflow for a New Academic Repo
1. Confirm the need for a new repo.
2. Name repo under correct **Team**.
3. Initialize with:
- README.md (use template below)
- LICENSE (if public)
- .gitignore
4. Add contributors.
5. Commit initial content in structured folders.
6. Maintain via PRs, reviews, and tagging.

---

## 7. README Template for New Academic Repos
[See README_TEMPLATE.md in this repo](./README_TEMPLATE.md) for the starter file.

---

## 8. Future Additions
This document will grow to include:
- File naming conventions 
- Curriculum versioning policy
- Archival process for outdated repos
- Automation (GitHub Actions for doc formatting/checks)
