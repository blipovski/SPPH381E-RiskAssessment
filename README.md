# SPPH 381E Project Website

👋 Welcome to my Project Website repository 👋

This website is the result of my examination into the health and occupational hazards associated with receipt paper. This project was submitted as part of the risk assessment assignment for the SPPH 381E (Work & Health) course at the University of British Columbia during the spring semester of 2024. Designed using Hugo, a static site generator written in Go, this website uses the Hextra theme to host an engaging and accessible space to share my findings and insights.

The SPPH project website, hosted at https://spph.lipovski.ca, is structured to guide visitors through the intricate details of receipt paper's impact, from production to disposal. The website is divided into main sections: Introduction, Background, Life Cycle Assessment, and Risk Assessment, providing a clear and linear progression of information.

# Features

- **Documentation-Style Layout:** Information is organized in a logical sequence, making it easy to navigate and understand the complex subject matter.
- **Interactive Elements:** Utilize previous and next buttons for smooth navigation between sections, and access various topics through the sidebar or homepage buttons.
- **Comprehensive Analysis:** The website consolidates a wealth of research findings, presenting them in a user-friendly digital format.

# Hugo

This project is built using the Hugo static site generator, leveraging the versatile Hextra theme for its design and structure. To learn more, visit the [Hugo website](https://gohugo.io).

# Hugo Hextra

To use this Hugo theme, visit the [Hextra Repository](https://github.com/imfing/hextra).

## Quick Start

Use this template to create your own repository:

<img src="https://docs.github.com/assets/cb-77734/mw-1440/images/help/repository/use-this-template-button.webp" width=400 />

You can also quickly start developing using the following online development environment:

- [GitHub Codespaces](https://github.com/codespaces) 
    
    [![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/imfing/hextra-starter-template)

    Create a new codespace and follow the [Local Development](#local-development) to launch the preview

- [Gitpod](https://gitpod.io)

    [![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/imfing/hextra-starter-template)


## Deployment

### GitHub Pages

A GitHub Actions workflow is provided in [`.github/workflows/pages.yaml`](./.github/workflows/pages.yaml) to [publish to GitHub Pages](https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/) for free. 

For details, see [Publishing with a custom GitHub Actions workflow](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-with-a-custom-github-actions-workflow).

Note: in the settings, make sure to set the Pages deployment source to **GitHub Actions**:

<img src="https://github.com/imfing/hextra-starter-template/assets/5097752/99676430-884e-42ab-b901-f6534a0d6eee" width=600 />

[Run the workflow manually](https://docs.github.com/en/actions/using-workflows/manually-running-a-workflow) if it's not triggered automatically.

### Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/imfing/hextra-starter-template)

### Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fimfing%2Fhextra-starter-template&env=HUGO_VERSION)

Override the configuration:

<img src="https://github.com/imfing/hextra-starter-template/assets/5097752/e2e3cecd-c884-47ec-b064-14f896fee08d" width=600 />

## Local Development

Pre-requisites: [Hugo](https://gohugo.io/getting-started/installing/), [Go](https://golang.org/doc/install) and [Git](https://git-scm.com)

```shell
# Clone the repo
git clone https://github.com/imfing/hextra-starter-template.git

# Change directory
cd hextra-starter-template

# Start the server
hugo mod tidy
hugo server --logLevel debug --disableFastRender -p 1313
```

### Update theme

```shell
hugo mod get -u
hugo mod tidy
```

See [Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules) for more details.

# License

This project is licensed under the MIT License - see the LICENSE.md file for details.

# Acknowledgments

Thanks to the creators of Hugo and the Hextra theme for making this project possible. Special thanks to Dr. Robert Macpherson and the SPPH 381E course team for their support and guidance throughout the project's development.