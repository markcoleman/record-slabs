# Record Slabs Dev Workspace

This repository provides a ready-to-use development environment configured to work with the Databricks CLI. The workspace is built around a Debian-based dev container that automatically installs the CLI, making it easy to manage and interact with your Databricks resources directly from the command line.

## Overview

The Record Slabs workspace is designed for users who need to:

- Interact with Databricks clusters, jobs, and notebooks via the command line.
- Leverage a consistent and reproducible development environment.
- Quickly set up and extend Databricks CLI workflows without complex installation steps.

This environment uses a Debian Bullseye base image and installs the Databricks CLI using a streamlined curl command.

## Features

- Debian-Based Container: Uses mcr.microsoft.com/devcontainers/base:bullseye for compatibility and stability.
- Automated CLI Installation: The dev container automatically installs the Databricks CLI using a curl command in the post-creation phase.
- Ready to Extend: Customize and expand your workspace by modifying the Dockerfile or the devcontainer.json file.

## Getting Started

### Prerequisites

- Docker
- Visual Studio Code with the Remote - Containers extension

### Setup

1. Clone the Repository:
1. Open in VS Code:
Open the repository in Visual Studio Code. You should be prompted to reopen the workspace in a container. If not, use the Remote-Containers: Reopen in Container command from the Command Palette.
