# Contributing Guidelines for Llama Prompts

Thank you for considering contributing to Llama Prompts! This document outlines the process for adding prompts to the csv file used by the project.

## Adding Prompts

1. Fork the repository and clone it locally.

2. Navigate to the `prompts` folder and open the `prompts.csv` file.

3. Add your prompts in the following format: ```Prompt name, Prompt, 7B, 13B, 30B, 65B, Source```

- `Prompt name` should be a string enclosed in quotation marks summarizing the purpose of the prompt. Please keep the Prompt name concise and under 10 words.
- `Prompt` should be a string enclosed in quotation marks representing the text of the prompt.
- `7B, 13B, 30B, 65B` should be a boolean (TRUE / FALSE / NULL if untested) informing whether or not the prompt produces expected behaviour on each individual model.
- `Source` should be the source of the prompt enclosed in quotation marks. If you made it yourself, your github profile link goes here.

4. Save the `prompts.csv` file.

5. Commit your changes with a descriptive commit message.

6. Push your changes to your fork.

7. Open a pull request on the main repository. In your pull request description, please include a brief summary of the prompts you have added and any relevant context or details.

## Code of Conduct

Llama Prompts has adopted a Code of Conduct that we expect all contributors to adhere to.

1. Be respectful: Treat others with kindness and respect. Avoid making personal attacks or derogatory comments.

2. Communicate effectively: Use clear and concise language in your comments and commit messages. Be open to feedback and willing to discuss any issues that arise.

3. Be collaborative: Work together with other contributors to improve the project. Be open to suggestions and willing to compromise.

4. Give credit where it's due: Acknowledge the contributions of others in your commit messages and comments.

5. Be professional: Avoid using inappropriate language or behavior. Remember that this is a public forum and your actions reflect on both yourself and the project.

Remember that the goal of a Git repository is to collaborate and build something together. By treating each other with respect and working together, we can achieve great things.


## License

By contributing to Llama Prompts, you agree that your contributions will be licensed under the project's [CC License](LICENSE).

Thank you for contributing to Llama Prompts!