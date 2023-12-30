# Contributing to Kenyan Banks and Branches

Thank you for considering contributing to the Kenyan Banks and Branches repository! This project aims to provide comprehensive information about Kenyan banks and their branches, including bank names, codes, branch names, branch codes, and M-Pesa Paybill numbers.

## How to Contribute

To contribute to this repository, follow these steps:

1. Fork the Repository:
    - Click the "**Fork**" button at the top right of the repository page. This will create a copy of the repository in your GitHub account.

2. Clone the Repository:
    - Clone your forked repository to your local machine.

    ```
    git clone https://github.com/your-username/kenyan-banks-and-branches.git
    cd kenyan-banks-and-branches
    ```

3. Create a Branch:
    - Create a new branch for your contribution. Use a descriptive branch name that reflects the nature of your contribution.

    ```
    git checkout -b feature/add-paybill-numbers
    ```

4. Contribute by adding a bank's M-Pesa Paybill number:

    Open the `banks-and-branches.json` file in the repository.
    Fill in the missing M-Pesa Paybill numbers for the respective banks.
    Ensure that the data format is consistent with the existing entries.

5. Commit Changes:

    Commit your changes with a clear and concise commit message.

    ```
    git add banks-and-branches.json
    git commit -m "Add M-Pesa Paybill number for {the-bank-name} Bank."
    ```

6. Push Changes:

    Push your changes to your forked repository.

    ```
    git push --set-upstream origin {your-branch-name}
    ```

7. Create a Pull Request:

    Open a pull request (PR) on the original repository. Ensure that the PR title and description clearly describe your contribution.
    
    Reference any relevant issues in your PR description.