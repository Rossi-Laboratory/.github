**Rossi Laboratory GitHub Management Policy**

### **1. General Guidelines**
- All repositories should be properly documented with a **README.md** file.
- Follow the established **branching strategy** (e.g., main → dev → feature branches).
- Use **clear and meaningful commit messages** to track changes effectively.
- Ensure that **all code follows the lab's coding style and best practices**.

### **2. File Storage & Data Management**
- **Do not upload large files** (e.g., datasets, trained models, raw logs) to GitHub.
- Large files should be stored in the **GitHub Shared Folder** or an external storage service.
- Use **.gitignore** to exclude unnecessary files such as temporary logs, local configurations, and build artifacts.
- If necessary, use **Git LFS (Large File Storage)** for versioning large files, but avoid excessive use.

### **3. Collaboration & Permissions**
- **Pull requests (PRs) must be reviewed** before merging into the main branch.
- Use **issue tracking** to manage tasks, bugs, and feature requests.
- Assign appropriate **access levels** to team members based on their roles.
- Sensitive information (e.g., API keys, credentials) **must not be stored in repositories**. Use environment variables or secret management tools instead.

### **4. Security & Compliance**
- Regularly update dependencies to **patch security vulnerabilities**.
- Do not share private repositories outside the lab without approval.
- Report any security concerns or suspicious activities to the lab administrator immediately.

### **5. Repository Cleanup & Maintenance**
- Archive inactive repositories instead of deleting them.
- Periodically **remove unused branches** and clean up stale issues.
- Keep repositories **organized and well-documented** to ensure ease of access and understanding.

### **6. Enforcement & Updates**
- Failure to comply with these policies may result in restricted access to the lab’s GitHub repositories.
- This policy will be reviewed and updated as necessary to align with best practices and technological advancements.

For any questions or clarifications, please contact the **Rossi Lab GitHub Administrators**.
