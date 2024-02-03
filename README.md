# For Development

To contribute to this project, follow these steps:

## Fork the Repository

-  Click the "Fork" button at the top right of this repository. This will create a copy of the repository in your own GitHub account.

## Clone the Repository

-   ### Clone your forked repository to your local system using the following command:

    `git clone https://github.com/your-username/your-project-name.git`

## Make Changes

-   ### Make your changes to the code and save your files.

## Commit and Push

-   ### Stage your changes:

    `git add .`

-   ### Commit your changes with a descriptive message:

    `git commit -m "Description of the changes made"`

-   ### Push your changes to your forked repository:

    `git push origin feature-name`

## Syncing with the Main Repository

-   ### Add the original repository as a remote:

    `git remote add upstream https://github.com/gautam-mh/News-App.git`

-   ### Fetch the latest changes from the main repository:

    `git fetch upstream`

-   ### Update your local main branch to match the upstream main branch:

    `git checkout main`
    
    `git merge upstream/main`

-   ### Push the updated main branch to your fork:

    `git push origin main`

That's it! You've successfully forked the project, made changes, and created a pull request for your contributions. Happy coding!
