# Marp Slides [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) [![workflow](https://github.com/thibaudmartinez/marp-slides/actions/workflows/main.yml/badge.svg)](https://github.com/thibaudmartinez/marp-slides/actions)

This is a template repository to create slides using [Marp](https://marp.app/). It leverages [GitHub Actions](https://docs.github.com/en/actions) to automate the generation of PDF and HTML slides from Markdown source files.

## Usage

* Write your slides as [Marpit Markdown](https://marpit.marp.app/markdown) documents in [`src/`](./src).
* Commit your changes and push them to the remote repository.
* Changes in the [`src/`](./src) directory trigger a GitHub workflow that regenerates PDF and HTML slides and stores them in the [`slides/`](./slides) folder.
* Generated slides are automatically committed by the GitHub worflow. Run `git pull` to get the generated slides in their latest version.
 
## References

* [Marp: Markdown Presentation Ecosystem](https://marp.app/)
* [git-auto-commit Action](https://github.com/stefanzweifel/git-auto-commit-action)

## License

The repository content is [MIT licensed](https://opensource.org/licenses/MIT).
