# Python開発環境

DecContainerを使用したPythonの開発環境のテンプレートです。リンターやフォーマッターにRuffを採用しています。

## 使い方

### 必要なもの

- [Visual Studio Code (VS Code)](https://code.visualstudio.com)
- [Docker](https://www.docker.com/products/docker-desktop)
- [Remote Containers (VS Codeの拡張機能)](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

### 手順

自分のプロジェクト名を指定してリポジトリをクローンします。

```
git clone git@github.com:whitebearman/pyhhon-env-basic.git [your-project-name]
```

`myproject` ディレクトリの名前を、クローンするときに指定した`[your-project-name]` に変更します。

クローンしたディレクトリをVS Codeで開きます。

その後、コマンドパレットで `Reopen in Container` を選択して、リモートコンテナを開きます。

### 特徴

- Python 3.10
- Docker
- Ruff(Pythonのリンター、フォーマッター)
- Git
- 分析に必要な基本的なPythonライブラリ(numpy, pandasなど)

# Python Development Environment with Devcontainer, Docker Compose, and Ruff

This repository contains a development environment setup for Python projects using Visual Studio Code's Remote - Containers extension, Docker Compose, and Ruff for linting and formatting.

## Getting Started

1. Install [Visual Studio Code](https://code.visualstudio.com/), the [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension, and [Docker](https://www.docker.com/products/docker-desktop).
2. Clone this repository.
3. Open the cloned repository in Visual Studio Code.
4. When prompted, click "Reopen in Container" or run the "Remote-Containers: Reopen in Container" command from the Command Palette (F1).

Visual Studio Code will use Docker Compose to build the container and set up the development environment with Ruff for linting and formatting.

## Features

- Python 3.10 environment
- Docker Compose for easy service management
- Ruff for fast and efficient linting and formatting
- Git support
- VS Code extensions for Python development and Ruff integration

## Customization

Feel free to modify the `devcontainer.json`, `Dockerfile`, `docker-compose.yml`, and `pyproject.toml` to suit your specific needs. You can adjust Ruff rules, add more services, or install additional dependencies as required.
