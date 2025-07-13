Issue prompt generator
Please analyze this GitHub issue or feature: $ARGUMENTS

Follow these steps:

1. Use `gh issue view` to get the issue details.
2. Think hard and craft a prompt that we can pass to an LLM to get it to complete this work successfully.
3. Ensure the prompt will be accurately understood by the given target.
4. Export the prompt as a temporary .md file into the planningdocs directory.

Remember to use the GitHub CLI (`gh`) for all GitHub-related tasks.
