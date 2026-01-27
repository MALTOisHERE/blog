# Med. AIT OUAARAB - Blog

Welcome to the source code of my personal blog, where I write about Cyber Security and Technology.

**Live Site:** [https://blog.malto.icu](https://blog.malto.icu)

## 🛠 Tech Stack

This blog is built using the following technologies:

-   **Static Site Generator:** [Hugo](https://gohugo.io/)
-   **Theme:** [Hugo Theme Stack](https://github.com/CaiJimmy/hugo-theme-stack)
-   **Comments:** [Giscus](https://giscus.app/)

## 🚀 Getting Started

To run this project locally, follow these steps:

### Prerequisites

Ensure you have [Hugo](https://gohugo.io/installation/) installed on your machine. This project requires **Hugo Extended**.

### Installation

1.  Clone this repository:

    ```bash
    git clone https://github.com/MALTOisHERE/blog
    cd blog
    ```

2.  This project uses Hugo Modules. You can initialize dependencies by running:

    ```bash
    hugo mod get
    ```

### Running Locally

Start the Hugo development server:

```bash
hugo server
```

Navigate to `http://localhost:1313/` in your browser to view the site.

## 📝 Configuration

The site configuration is split into multiple files under the `config/_default/` directory.

-   `config.toml`: Main configuration (Base URL, Title, etc.)
-   `params.toml`: Theme parameters (Footer, Sidebar, Widgets, Comments, etc.)
-   `menu.toml`: Menu definition

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
