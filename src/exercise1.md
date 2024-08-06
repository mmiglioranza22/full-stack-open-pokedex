The points to discuss:

- Q: Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by Google.

A: For a proyect developed in Java, firstly we would need to decide which CI platform to use. If its on-premise, Jenkins with its various plugins will be used. For cloud-based hoisting, Gitlab, Github-actions, Bitbucket-pipelines or CircleCI can be used. The linting and testing will be those inherent to the proyect, using Playwright or Cypress for E2E or smoke testing (there could be a QA Manual test if the proyect requires it and can afford it)

- Q: What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask Google!

A: Already answered.

- Q: Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

A: It depends entirely on the proyect and the intended use and targeted audience, and requirements (security, budget, down-time, etc.)
A localized customer specific software (banking) might need its on-premise hoisting due to client's requirements. An extensively available web application might perform and be served better with a cloud-based solution
