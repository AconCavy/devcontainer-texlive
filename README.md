# devcontainer-texlive

The devcontainer template for the LaTeX using TeX Live.

## Requirement

- Visual Studio Code
- Remove Development (VSCode Extension)
- Docker
- [AconCavy/devcontainer-texlive-dockerfile](https://github.com/AconCavy/devcontainer-texlive-dockerfile)

## Default installed languages

- Japanese
- English

## LaTeX recipes

- LuaLaTex
- XeLaTex
- upLaTex

## Getting started

### Prepare a base image

1. Clone a base dockerfile repository from [AconCavy/devcontainer-texlive-dockerfile](https://github.com/AconCavy/devcontainer-texlive-dockerfile).
1. Build the base image named `devcontainer-texlive` using `build-image.cmd` or `build-image.sh` in the cloned repository.

### Setup devcontainer

1. Create a new repository from this repository template.
1. Clone the created repository to your workspace.
1. Open the project using Visual Studio Code.
1. If you built the base image of another name, you should specify your built image in `.devcontainer/Dockerfile`.
1. Connect to a remote workspace from 'Open Folder in Container' in the Remote Explorer.
1. Create any TeX file.
1. Build LaTex Project using a recipe from the `latex-workshop` Visual Studio Code extension.
1. The result will be exported to `out` directory.
