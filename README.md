# Auto Commit

<!-- ![Build Status](https://img.shields.io/github/actions/workflow/status/shoot649854/vaulted-zodiac/ci.yml?branch=main)
![License](https://img.shields.io/github/license/shoot649854/vaulted-zodiac)
![Version](https://img.shields.io/github/package-json/v/shoot649854/vaulted-zodiac?private=true)
![Dependencies](https://img.shields.io/librariesio/github/shoot649854/vaulted-zodiac?private=true)
![Dev Dependencies](https://img.shields.io/librariesio/github/shoot649854/vaulted-zodiac?private=true&type=dev)
![Issues](https://img.shields.io/github/issues/shoot649854/vaulted-zodiac) -->
<!-- ![Python](https://img.shields.io/badge/-Python-F9DC3E.svg?logo=python&style=flat) -->
<!-- ![Flask](https://img.shields.io/badge/-Flask-000000.svg?logo=flask&style=flat) -->
<!-- ![Python Version](https://im/g.shields.io/badge/python-3.11-blue) -->

![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC.svg?logo=typescript&style=flat)
![React](https://img.shields.io/badge/React-18.3.3-blue)
![Node](https://img.shields.io/badge/Node-20.14.10-green)

## Description

Description

### Branch Naming Rules

| Branch Name                    | Description            | Supplemental |
| ------------------------------ | ---------------------- | ------------ |
| main                           | latest release         |              |
| dev/main                       | latest for development |              |
| hotfix/{module name}/{subject} | Hotfix branch          |              |
| sandbox/{anything}             | test code, etc.        |              |

### Basic Branch Operation Rules

-   Work is branched from each latest branch
-   Delete working branches after merging
-   Review as much as possible (have someone do it for you)
-   Build, deploy, etc. are discussed separately.

## Prerequisites

-   Python 3.11
-   Docker
-   Docker Compose
-   Homebrew (for installing Graphviz)

## Dependencies

| Package                          | Version |
| -------------------------------- | ------- |
| python                           | ^3.11   |
| flask                            | ^3.0.3  |
| flask-migrate                    | ^4.0.7  |
| sqlalchemy-data-model-visualizer | ^0.1.3  |

## Steps

1. **Clone the Repository**

    ```bash
    git clone https://github.com/
    cd
    ```

## Deployment

### Environment file

PROJECT_ID and REGION is required to have before deploying.

```bash

```

## Commit message

Please refer to the following template for the commit message.

```plaintext
🐞 Bugs and Performance
#🐛 :bug: bug fixes.
#🚑 :ambulance: fix a critical bug
#🚀 :rocket: performance improvements
#💻 Code quality and style
#👍 :+1: feature improvements
#♻️ :recycle: refactoring
#👕 :shirt: Lint error fixes and code style fixes

🎨 UI/UX and design
#✨ :sparkles: add new features
#🎨 :art: design changes only

🛠️ Development Tools and Settings.
#🚧 :construction: WIP (Work in Progress)
#⚙ :gear: config change
#📦 :package: add new dependency
#🆙 :up: update dependency packages, etc.

documentation and comments.
#📝 :memo: fix wording
#📚 :books: documentation
#💡 :bulb: add new ideas and comments

🛡️ security
#👮 :op: security-related improvements

🧪 testing and CI.
#💚 :green_heart: fix/improve testing and CI

🗂️ file and folder manipulation.
#📂 :file_folder: Folder manipulation
#🚚 :truck: file movement

#📊 :log: logging and tracking
#💢 :anger: conflicts
#🔊 :loud_sound: add log
#🔇 :mute: log deleted.
#📈 :chart_with_upwards_trend: add analytics or tracking code

💡 Other.
#🧐 :monocle_face: code reading and questions.
#🍻 :beers: code that was fun to write.
#🙈 :see_no_evil: .gitignore addition.
#🛠️ :hammer_and_wrench: bug fixes and basic problem solving
```
