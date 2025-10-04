# Jira Integration Demo

This repository was created for training purposes to demonstrate integration between **Jira** and **GitHub**.  
It is used as a practice project for QA activities such as:

- Creating and managing issues in Jira (Tasks, Bugs, Autotests).
- Linking commits and pull requests to Jira issues.
- Practicing bug reporting and task tracking workflow.
- Understanding the connection between development and QA processes.
- Writing and documenting **automated tests** (PHPUnit, Laravel) as part of QA practice.

---

## Purpose
The main goal of this repository is to serve as a **QA practice project**.  
It does not contain production-ready code but helps to show how QA work is organized in a real project environment.  

All training activities are based on a **real working project** – [flyn.no](https://flyn.no/).  
This allows us to practice QA processes (manual testing, bug reporting, automated testing) in conditions close to a real production system.

---

## Examples

Here are examples of how QA tasks are connected across different tools:

### Manual Testing
- [QPP-1] **Login form – email field does not validate correctly**  
  (Jira Bug report with screenshots – PDF available in `/docs`)

### Automated Testing
- [QPP-2] **[AUTOTEST] Login form – successful login redirects to dashboard**  
  - Jira task: exported as PDF in `/docs`  
  - Test code: [`tests/Feature/Auth/AuthenticationTest.php`](tests/Feature/Auth/AuthenticationTest.php)  
  - Related test method: `test_users_can_authenticate_using_the_login_screen`

Future examples will include both **manual bug reports** and **automated tests** to demonstrate the full QA workflow.

---

## Author
**Yurii Matviiv**  
QA Intern candidate, Oslo, Norway
