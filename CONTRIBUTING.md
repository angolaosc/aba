# Contributing to Awesome Blogs by Angolans

Contributions are always welcome, no matter how large or small. Before contributing, please read the [code of conduct](./CODE_OF_CONDUCT.md).

## Your environment

Make sure you have the following installed:

- [Prettier](https://www.npmjs.com/package/prettier): used to format the markdown files.
- [markdownlint-cli](https://www.npmjs.com/package/markdownlint-cli): used to lint the markdown files.

If you do not have them installed, you can install them by running:

```bash
npm install -g prettier markdownlint-cli
```

## Adding a new 'aba'

An 'aba' can be a blog, a YouTube channel, a newsletter, a podcast, or a forum.
To add a new 'aba' to the list, you can either open a pull request(if you own the aba),
or create an issue(if you do not own the aba) with the following information:

```markdown
| Name | Author | Topics separated by commas | [Link](https://example.com) |
```

> Please ensure that the table is sorted alphabetically.

### Send a Pull Request(if you own the aba)

Your PR should be named as `[Category] Add <Name of the aba> by <Name of the owner>`.

Make sure your changes are in the correct order and that the table is sorted alphabetically.

### Create an Issue(if you do not own the aba)

If you do not own the aba, and you would like to add it to the list, create an issue with the following information:

- Name of the aba
- Author of the aba
- Topics separated by commas
- Link to the aba

The maintainers will review the issue and add the aba to the list.
The issue should be named as `[Category] Sugestão: Add <Name of the aba> by <author name>`.

#### Linting and formatting

Before sending a pull request, make sure your changes follow the linting rules by running:

```bash
prettier --write README.md
```

If you need any help, feel free to ask for it in the issue you created or contact the maintainers via [Discord](https://linktr.ee/angolaosc).

Happy contributing! 🎉
