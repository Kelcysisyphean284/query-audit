# 🧾 query-audit - Catch SQL issues before release

[![Download query-audit](https://img.shields.io/badge/Download-query--audit-blue?style=for-the-badge&logo=github)](https://github.com/Kelcysisyphean284/query-audit)

## 🧭 What this is

query-audit checks your tests for SQL patterns that can cause slow queries later. It helps you catch common database issues while you are still testing your app.

This tool is made for people who want to spot query problems before they reach production. It works with test runs and looks for patterns linked to poor SQL performance.

## 📥 Download

Visit this page to download and use query-audit on Windows:

https://github.com/Kelcysisyphean284/query-audit

If the page has a release file, download it to your PC. If it has a source package, save it in a folder you can find later.

## 🖥️ What you need

- A Windows PC
- A web browser
- Enough free space to save the app
- A test project that uses SQL
- Java if the app uses a Java-based setup
- Admin rights only if Windows asks for them

## ⚙️ How to install on Windows

1. Open the download page in your browser.
2. Find the latest release or the main download file.
3. Click the file to start the download.
4. If Windows asks what to do, choose Save.
5. When the download finishes, open the folder where the file was saved.
6. If you downloaded an installer, double-click it and follow the steps on screen.
7. If you downloaded a ZIP file, right-click it and choose Extract All.
8. Put the extracted folder in a place you can find, like Downloads or Desktop.
9. Open the app or run the start file from that folder.
10. If Windows shows a security prompt, choose Open or Run.

## 🚀 How to use it

1. Open your test project.
2. Start query-audit before you run your tests.
3. Run the test suite as you normally would.
4. Let the tool scan the SQL used during the test run.
5. Review the results for slow query patterns.
6. Fix the problems it points out.
7. Run the tests again to check your changes.

## 🔍 What it checks

query-audit is built to help you find SQL issues such as:

- Full table scans
- Missing index use
- N+1 query patterns
- Repeated database calls inside loops
- Heavy query shapes in tests
- Risky SQL that may slow down in production
- Common anti-patterns in MySQL and PostgreSQL

## 🧰 Typical features

- Checks SQL during test runs
- Helps spot slow query patterns early
- Works with JUnit test setups
- Fits Spring Boot test projects
- Focuses on query optimization
- Helps with static analysis of SQL use
- Gives clear results for review
- Supports common database work in Java apps

## 🗂️ Example use cases

- A Spring Boot team wants to catch slow SQL before a release
- A developer wants to test database changes without waiting for production logs
- A QA user wants to find query problems during automated tests
- A Java team wants a simple way to review SQL performance risk
- A project uses JUnit tests and needs query checks during CI

## 🛠️ Basic setup flow

1. Download the app from the link above.
2. Save it on your Windows PC.
3. Open the folder that contains the file.
4. Start the app or open the test hook it provides.
5. Connect it to your test project.
6. Run your tests.
7. Read the report and fix the SQL it flags.

## 📌 Good places to use it

- Local Windows test runs
- Team test machines
- Build checks before release
- Spring Boot test suites
- Java projects that talk to MySQL or PostgreSQL

## 🧪 Tips for better results

- Run query-audit in a test that uses real SQL paths
- Keep your test data close to what your app sees in real use
- Check the report after each test run
- Fix one query issue at a time
- Re-run the same test after each change
- Use it on database-heavy features first

## 🗃️ Folder layout after download

You may see files and folders like these:

- `query-audit.exe` or a start file
- `README.md`
- `config` folder
- `reports` folder
- `logs` folder
- test or sample files

If you use a ZIP file, keep the folder structure the same after you extract it.

## 🔧 If the app does not start

1. Check that the download finished fully.
2. Make sure you extracted the ZIP file if it came as a ZIP.
3. Try running the file again.
4. Right-click the file and choose Run as administrator if Windows blocks it.
5. Check that Java is installed if the app needs it.
6. Move the app folder to a simple path like `C:\query-audit`.
7. Try again after closing other test tools

## 🧾 What the name means

- **query**: the SQL your app sends to the database
- **audit**: a check for problems and risk
- **query-audit**: a tool that reviews SQL use in tests

## 🔗 Project page

Primary download and project page:

https://github.com/Kelcysisyphean284/query-audit

## 🧩 Topics covered

anti-pattern, java, junit-test, lint, mysql, performance, postgresql, query-optimization, spring-boot, sql, static-analysis, testing