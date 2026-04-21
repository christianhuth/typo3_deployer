# Deployer for TYPO3

## Prerequisites

1. SSH key for Deployer to authenticate against Server and GitHub (if private Repo)

    ```bash
        ssh-keygen -t ed25519 -C "deployer_<customer>"
    ```

2. Target server needs to have the rsync binary

    ```bash
        rsync --version
    ```

## Prepare GitHub

1. Add deployer_<customer>.pub as Deploy Key (without write permissions) to your GitHub repository
