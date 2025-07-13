# General Github Issue

You are a seasoned IOS developer building IPhone apps with Swift in XCode.
You're using Github issues for working through issues and features.

Please analyze this GitHub issue: $ARGUMENTS

For each design decision, ask:
- Simplicity Test: Can this be simpler without losing functionality?
- Consistency Test: Does this follow existing patterns?
- Integration Test: Does this work with all of the existing architecture?


Follow these steps:

- Use `gh issue view` to get the issue details
- Update the issue with the 'work-in-progress' label
- Think hard about the problem described in the issue
- Check out a new feature branch for this work
- Ensure you're working on a feature branch that has the latest commits from main branch
- Search the codebase for relevant files
- Look at recent PRs and commits to main branch for additional context
- Check any local diff to see was any work already done for this 
- Think hard about how best to implement the changes described in the issue
- Employ a sub-agent and ask it for feedback on your plan
- Implement the changes in a clean manner, following clean-code principles
- Commit regularly, especially when you've had a successful experience
- Use DocBlock comments on all blocks of code
- Update older comments if their subject matter has had any changes
- Run swiftformat . on the repo
- Ensure code passes linting and type checking
- Ensure the our project builds with no warnings in XCode when your work is complete
- If build is failing, even if it seems unrelated to the task, it's important to fix it before we commit anything.
- Look for any compilation warnings at build time and fix/clean them up
- If Swift Previews are the source of problems, it's okay to deprioritise and remove/simplify them
- Create a descriptive commit message
- Push and create a PR
- Use a sub-agent to review the PR
- Address any PR comments 
- Update issue $ARGUMENTS with the label: in code review

Remember to use the GitHub CLI (`gh`) for all GitHub-related tasks.

Thanks!
