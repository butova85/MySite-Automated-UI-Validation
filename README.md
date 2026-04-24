 ---MySite Automated UI Validation... IN PROGRESS

This is my first project in creating automated test cases for web interfaces. With a master's degree in automation engineering, I decided to apply a systematic engineering approach to ensure the quality of my personal web portfolio.

The idea for this repository was inspired by a conversation with an Esri recruiter, who mentioned that the team thoroughly tests and "clicks through every button" on candidates' personal sites. I took this not just as a comment, but as a direct technical requirement. To guarantee the flawless performance of my site and save the reviewers' time, I developed this automated UI validation suite.

---Tools:

- Python: The core programming language for the test logic.

- Playwright: The browser automation framework (the "virtual hands" of the project) used to simulate real user interactions.

- Behave: A BDD (Behavior-Driven Development) tool that describes test scenarios in plain English (Gherkin syntax), seamlessly bridging them with the underlying code.

- GitHub Actions (CI/CD): The "cherry on top." A fully automated pipeline that triggers the test suite independently and updates the repository's status badge, ensuring the portfolio is always interview-ready.

---Automation Goals:

- Validate the functionality of navigation and all external links.

- Ensure the availability of key sections.

- Practice building stable and maintainable automated tests before transitioning to automation within the ArcGIS Online environment.
