# IntegrityChecker

GitHub Action that generates a SHA256 hash for a specified file or folder in your repository upon every merge to the main branch, ensuring data integrity and providing traceability with each commit ID.

## Usage

This action is defined by the `.github/workflows/IntegrityChecker.yml` file in your repository.

### Setup

1. Copy the contents of `.github/workflows/IntegrityChecker.yml` from this repository into the same path in your repository.
2. Set the `TARGET_FOLDER` variable in the `env` field of the `IntegrityChecker.yml` file to the path of the folder or file you want to create a check.

### Output

This action prints the hash generated for the folder/file and also the commit ID (SHA) that generated that.
