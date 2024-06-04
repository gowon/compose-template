# My Docsify Website Template

This is a template for creating a docsify-based web application.

## 1. Developing

For Windows users, you can install of the required and recommended development tools using the Chocolatey package manager.

1. Install Chocolatey on your machine using the [individual installation instructions](https://chocolatey.org/install#individual)

2. In a command prompt with Administrator privileges, run the following command from the project root folder:

  ```powershell
  choco install .\solution.chocolatey.config --confirm
  ```

References:

- <https://www.svgrepo.com/svg/333309/readme>
- CSS Themes and Colors
  - <https://dev.to/abbeyperini/dark-mode-toggle-and-prefers-color-scheme-4f3m>

## 2. Running Locally

The documentation is best viewed as a static website (powered by [docsify](https://docsify.js.org/)). To run the documentation website locally, you can run the [`dotnet-serve`](https://github.com/natemcmaster/dotnet-serve) tool:

```powershell
dotnet tool restore
dotnet serve --open-browser
```

When running, the website can be accessed through <http://localhost:3080>.
