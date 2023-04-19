1. Create a fork of the original repository:

        Go to the GitHub page of the original repository and click on the "Fork" button in the top right corner to create a fork of the repository under your GitHub account.
2. Clone your forked repository:

        On your GitHub account, go to the repository page of the forked repository.
        Click on the "Code" button and copy the repository URL.
        Open a terminal or command prompt and navigate to the directory where you want to clone the repository.
        Run the following command to clone the repository to your local machine:
        <git clone <REPOSITORY_URL>>
        Replace <REPOSITORY_URL> with the URL of your forked repository.

3. Create a branch for your changes:

        Run the following command to create a new branch for your changes:
        <git checkout -b my-feature-branch>
        Replace my-feature-branch with a descriptive name for your branch, such as fix-bug-123 or add-new-feature.

4. Make your changes and commit:

        Make your desired changes to your local copy of the project.
        Stage and commit your changes using the following commands:
        <git add .
         git commit -m "Description of my changes">

5. Push your branch to your forked repository:

        Run the following command to push your branch to your forked repository on GitHub:
        <git push origin my-feature-branch>
        Replace my-feature-branch with the name of your branch.

6. Create a pull request:

        Go to the GitHub page of your forked repository and click on the "Pull Requests" tab.
        Click on the "New pull request" button.
        Select the base repository (the original repository) and the base branch (typically master or main).
        Select your forked repository and your branch as the compare branch.
        Click on the "Create pull request" button.
        Provide a descriptive title and description for your pull request, and click on the "Create pull request" button to submit it.
7. Collaborate and iterate:

        Wait for feedback from the repository's maintainers and other contributors.
        Make further changes to your branch as needed based on feedback.
        Update your pull request with the changes and continue the discussion as necessary.
8. Merge the pull request:

        Once your pull request has been reviewed and approved, the repository's maintainers will merge it into the master branch.
        Once merged, you can update your local master branch with the latest changes by running the following commands:
        <git checkout master
         git pull upstream master>
        Replace upstream with the original repository's remote name, if you have added it with a different name.

