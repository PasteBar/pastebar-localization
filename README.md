
# PasteBar Localization Repository

Welcome to the PasteBar localization repository! This repository contains all the YAML files used for internationalizing the PasteBar application. We appreciate contributions to help improve the existing translations or add new languages. Follow the steps below to get started.

## How to Contribute

### 1. Fork the Repository

First, fork this repository to your GitHub account by clicking the "Fork" button in the top right corner of this page. This will create a copy of the repository under your GitHub account.

Repository URL: [PasteBar Localization](https://github.com/PasteBar/pastebar-localization)

### 2. Clone the Repository

After forking the repository, clone it to your local machine using the following command:

```bash
git clone https://github.com/your-username/pastebar-localization.git
```

Replace `your-username` with your GitHub username.

### 3. Create a New Branch

To keep your contributions organized, create a new branch for your work. Use a descriptive branch name, such as `fix-german-translation` or `add-spanish-language`:

```bash
cd pastebar-localization
git checkout -b your-branch-name
```

### 4. Make Your Changes

#### Correct Existing Translation

If you want to improve or correct an existing translation, navigate to the corresponding language folder (e.g., `de`, `fr`, etc.) and edit the YAML files.

For example, to update the German translation by editing the `common.yaml` file:

```bash
edit de/common.yaml
```

Use your favorite text editor to make the necessary changes. After making the necessary changes, save the file.

#### Add a New Language

To add a completely new language, follow these steps:

1. Copy the `en` folder to create a new folder for the language you want to add. Use the appropriate language code as the folder name.

```bash
cp -r en es-ES
```

1. Translate the content (values only) in the YAML files to the desired language inside all the `.yaml` files in the newly created folder.

Example:

```yaml
Day: Día
Days: Días
Month: Mes
Months: Meses
```

2. Ensure that the file structure and keys remain the same as in the `en` folder.

### 5. Commit Your Changes

Once you've made your changes, commit them to your branch:

```bash
git add .
git commit -m "Description of your changes"
```

### 6. Push Your Changes

Push your changes to your forked repository:

```bash
git push origin your-branch-name
```

### 7. Create a Pull Request

After pushing your changes, go to the original repository on GitHub. You should see a prompt to create a pull request (PR). Click on that and follow the instructions to submit your PR for review.

### 8. Wait for Review

Your pull request will be reviewed by the maintainers of the repository. They may request changes or approve your contribution directly.

### 9. Celebrate!

Once your contribution is merged, celebrate your successful contribution to the PasteBar project!

## Additional Notes

- Please make sure that all translations are accurate and consistent with the existing keys.
- Avoid making structural changes to the YAML files without discussing them first.
- If you have any questions, feel free to open an issue, and someone from the team will assist you.

Thank you for contributing to the localization of PasteBar!
