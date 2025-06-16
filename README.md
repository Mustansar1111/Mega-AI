Mega AI – Cypress End-to-End Automation Suite

Mega AI is a smart campaign management and analytics platform. I contributed as a **QA Automation Engineer**, implementing Cypress tests to ensure robust functionality across dynamic modules like login, dashboard analytics, campaign creation, pool segmentation, and more.

This repository showcases my test automation work using Cypress, integrated with GitHub CI, focused on reliability, maintainability, and real-time feedback loops.

---

🔍 Preview

> QA Portfolio – Cypress Testing for Mega AI
> Featuring test automation for Login, Dashboard, Campaigns, Pools, and Settings modules.

Screenshots:
- ![Login Page](./screenshots/Capture1)
- ![Dashboard](./screenshots/Capture 3)
- ![Campaign Settings](./screenshots/Capture4)

---

Tech Stack

| Layer           | Tools/Tech                         |
|-----------------|------------------------------------|
| Test Framework  | Cypress 12+                        |
| Language        | JavaScript / Node.js               |
| CI/CD           | GitHub Actions                     |
| Reporting       | Mochawesome, Allure Reports        |
| Version Control | Git + GitHub                       |
| Browser Support | Chrome, Electron                   |

---

🧪 Test Coverage

🔐 Authentication
- Valid & Invalid Login scenarios
- Error messages & password masking
- Token handling & logout flow

📊 Dashboard & Campaign Modules
- Dynamic data loads
- Table filters, search & pagination
- Create/Edit/Delete/Clone campaigns
- Modal validations

⚙️ Campaign Settings
- Toggles, switches & conditional form display
- Required fields & success messages
- API assertions (status code, response body)

🧩 Pools and Segments
- Tab navigation & form behavior
- Alert modals and confirmation flows
- Segment creation & deletion tests

---

🛠️ Project Structure

📁 cypress/
├── e2e/           # Test files organized by module
├── fixtures/      # Sample test data
├── support/       # Commands, hooks, config helpers
├── screenshots/   # Auto-captured on test failure
└── videos/        # Recorded test sessions (optional)

````

🔁 GitHub Actions CI Workflow

```yaml
name: Cypress E2E Tests
on: [push, pull_request]
jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Install Node.js
        uses: actions/setup-node@v3
        with:
          node-version: '18'
      - run: npm install
      - name: Run Cypress Tests
        uses: cypress-io/github-action@v5
        with:
          browser: chrome
          start: npm start
          wait-on: 'http://localhost:3000'
````

---

🔄 Branch Strategy

| Branch      | Purpose             |
| ----------- | ------------------- |
| `main`      | Live stable tests   |
| `develop`   | Ongoing QA work     |
| `feature/*` | Task-specific tests |

---

📈 Impact & Achievements

* ✅ Reduced manual regression testing time by **70%**
* 🐞 Identified & reported **50+ critical bugs**
* 📊 Achieved **90% test coverage** across key flows
* 🔄 Integrated Cypress with GitHub CI/CD for test automation

---

👨‍💻 About Me

I’m a QA Engineer with strong experience in automating tests using Cypress, API validations, and integrating test reports into CI/CD workflows. I specialize in:

* 🔍 Writing clean & scalable Cypress test cases
* 🔄 Debugging flaky tests & test retries
* 📊 Reporting with visual logs & analytics
* 🔗 Collaborating with devs in Agile teams

> 📫 Email:(mustansarriaz123@gmail.com)
> 🔗 [LinkedIn](https://www.linkedin.com/in/mustansar-riaz-5b2b8a125/)

---

🤝 Let’s Connect

If you’re looking for a freelance/remote QA engineer who can:

* Automate your critical workflows
* Improve QA efficiency
* Deliver fast, clean, testable results

➡️ Let’s collaborate!

```

--



