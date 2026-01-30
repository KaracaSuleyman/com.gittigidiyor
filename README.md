# GittiGidiyor Test Automation Task

This project is a Selenium-based test automation suite designed to test specific user scenarios on the GittiGidiyor platform using Java and JUnit.

## 🛠 Technologies & Tools
* **Language:** Java
* **Test Framework:** JUnit 4/5
* **Automation Tool:** Selenium WebDriver
* **Build Tool:** Maven

## 📋 Project Rules

### Writing Rules
* **Comments:** Code must include relevant comment lines to explain the test steps and logic.

### Naming Conventions
1. All names must end with their respective **type**.
   * e.g., `searchBoxText`, `addToCartButton`, `loginDropdown`.
2. **camelCase** must be used for all variables and method names.
3. Element types (button, text, dropdown, etc.) must be clearly appended to the variable name.

---

## 🚀 Git & GitHub Workflow

### GitHub DOs
* **Branching:** Create a new branch immediately after being added as a collaborator before starting any work.
* **Adding Files:** Do not use `git add .` blindly. Use the specific file path to push changes.
   * *Example:* `git add src/test/java/tests/GittiGidiyorTest.java`
   * (Tip: Right-click the file > Copy Path > Path from Content Root).
* **Syncing:** Always run `git pull` on the **main** branch before starting your development tasks.
* **Merging:** Perform the `git pull` on **main**, then switch back to your feature branch and **merge** main into it.
* **Integrity:** Constantly verify that you are on your specific branch and NOT on the main branch.
* **Commits:** Use the commit message format: `git commit -m "date name"`.

### GitHub DON'Ts
* **Main Branch:** Working or pushing directly to the **main** branch is strictly forbidden.
* **Communication:** Never push code without communicating with the team or obtaining approval.
* **Leadership:** If changes are required in a shared area, consult the **Lead** before proceeding.

---

## 🛠 How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/KaracaSuleyman/com.gittigidiyor.git](https://github.com/KaracaSuleyman/com.gittigidiyor.git)
