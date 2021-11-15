# Practicalli - Gitbook Template

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/practicalli/gitbook-template/build-book?style=for-the-badge)

GitHub template to create new GitBook projects, as used by Practicalli.

## Overview

Use this repository template to quickly create the structure of a GitBook project, including a GitHub Action to deploy the website to GitHub Pages and generate ebook formats as a release.

The GitBook Action caches the npm plugins to minimise the time taken to run.

## Using the template

Visit the practicalli/gitbook-template repository and select the **Use this Template** button

Enter the repository name and description for the new GitBook project and select **"Create repository from template"**

Configure the GitBookk project by editing the [`book.json`](book.json) file.

Define the navigation of the book using the [SUMMARY.md](SUMMARY.md) file.

Subsequent pushes of the content to the `main` branch  will create a new version of the website and publish that version on GitHub pages automatically.

## Publish GitBook PDF, Mobi, Epub formats

Generate a new version of each Ebook format by selecting **"Release"** in the new GitHub repository

Select **"Create a new Release"** or **"Draft a new Release"**

Define a version, title, and description for the release.

Select **Save**.  A new release of each Ebook should appear within a few minutes (depending on the size of the content).
