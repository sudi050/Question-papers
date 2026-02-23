# Contributing to the Exam Question Paper Repository

Thank you for considering contributing! This repository is a collective effort to help students prepare better by providing a centralized archive of past exam papers.

---

## 📂 Directory Structure

To keep the repository searchable and clean, please follow the existing hierarchy:

```text
.
├── [Year] Year BTech / MTech + Electives
│   └── [CourseID]_[Course Name]
│       └── [Academic Year (e.g., 2025-26)]
│           ├── Test 1.pdf
│           ├── Test 2.pdf
│           └── End Sem.pdf
```

---

## 🛠 How to Contribute

1.  **Fork** the repository and **Clone** it locally.
2.  **Add your files** following the naming and folder conventions.
3.  **Update the Subfolder README:** If you add a new course, you **must** update the `README.md` within the parent folder (e.g., `MTech + Electives/README.md`) to include the new link.
4.  **Commit & Push:** Use clear messages like `git commit -m "Add DS5617 GenAI papers and update README"`.
5.  **Open a Pull Request**.

---

## 📝 Updating Subfolder Indices

Whenever a new course is added, update the `README.md` in the respective year/program folder using the following format:

### Example: MTech + Elective Courses README
```markdown
# MTech + Elective Courses

## Courses Listed in the Directory
- [DS5003A Data Engineering](./DS5003A_%20Data%20Engineering/)
- [DS5004 Mathematics for Data Science](./DS5004_%20Mathematics%20for%20Data%20Science/)
... (add new courses here)

If you add new courses or years, please follow the same structure and naming conventions as in the root [README.md](../README.md).
```

---

## 🏷️ Naming Conventions

### 1. Folders
* **Course Folders:** `[CourseID]_[Course Name]` (e.g., `DS5007_ Deep Learning`).
* **Year Folders:** `YYYY-YY` format (e.g., `2025-26`).

### 2. Files
* **Preferred Names:** `Test 1.pdf`, `Test 2.pdf`, `End Sem.pdf`.
* **Solutions:** Append "Solutions" to the name (e.g., `Test 1 Solutions.pdf`).

---

## ✅ Quality Guidelines

* **Format:** **PDF** is mandatory for question papers.
* **Legibility:** Use apps like **Adobe Scan** or **Microsoft Lens**. Ensure scans are clear, flat, and cropped.
* **Privacy:** **Mandatory:** Remove your **Name** or **Roll Number** from the paper (blur or crop) before uploading.

---

## ⚖️ License
By contributing, you agree that your contributions will be licensed under the same license as the repository.