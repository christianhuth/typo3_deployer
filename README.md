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
