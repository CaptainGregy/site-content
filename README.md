# Site Content

![Logo](static/images/logo.png)

Welcome to the **Site Content** repository! This repository contains the Hugo-templated content and resources for our website.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Site Locally](#running-the-site-locally)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This repository holds the various content assets used on our Hugo-templated website, including articles, images, and other media. The purpose is to manage and version control all website content effectively.

## Getting Started

### Prerequisites

To work with this repository, you will need:

- [Git](https://git-scm.com/)
- [Hugo](https://gohugo.io/) (extended version recommended)
- A text editor like [VS Code](https://code.visualstudio.com/)

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/CaptainGregy/site-content.git
    ```
2. Change into the project directory:

   ```bash
   cd site-content
   ```

3. Install the required dependencies:

   ```bash
    hugo mod get -u
    ```

4. Start the Hugo server:

   ```bash
   hugo server
   ```

This will start a local server and you can view the site at http://localhost:1313. The server will automatically reload whenever you make changes to the content or templates.

5. Open your browser and navigate to `http://localhost:1313/` to view the site.

### Usage

This section outlines how to use the content in this repository.

    1.  Adding New Content: Create new Markdown files in the content directory.
    2.  Updating Content: Edit existing Markdown files in the content directory.
    3.  Customizing Templates: Modify the templates in the layouts directory to change the site’s appearance and structure.
    4.  Deploying the Site: Follow your deployment process, which typically involves building the site using hugo and deploying the public directory to your web server.
