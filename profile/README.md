<p align="center">
  <img src="https://raw.githubusercontent.com/illegalstudio/elephc/main/assets/logo-mark.png" alt="elephc logo" width="130">
</p>

<h1 align="center">elephc</h1>

<p align="center">
  <em>Write PHP. Ship a native binary.</em>
</p>

<p align="center">
  <a href="https://github.com/illegalstudio/elephc/stargazers"><img src="https://img.shields.io/github/stars/illegalstudio/elephc?style=flat-square&amp;logo=github&amp;logoColor=white&amp;label=stars&amp;color=FF7A1A" alt="Compiler stars"></a>
  <a href="https://github.com/illegalstudio/elephc/releases"><img src="https://img.shields.io/github/downloads/illegalstudio/elephc/total?style=flat-square&amp;logo=github&amp;logoColor=white&amp;label=downloads&amp;color=FF7A1A" alt="Compiler downloads"></a>
  <a href="https://github.com/illegalstudio/elephc/blob/main/LICENSE"><img src="https://img.shields.io/github/license/illegalstudio/elephc?style=flat-square&amp;color=FF7A1A" alt="License: MIT"></a>
</p>

<p align="center">
  <strong>PHP to native &middot; macOS &middot; Linux &middot; open source</strong>
</p>

<p align="center">
  Tools, experiments, and showcases around <a href="https://github.com/illegalstudio/elephc">elephc</a>, a compiler that turns a supported subset of PHP into native executables and libraries. Explore systems programming, build command-line tools, and bring PHP beyond the web.
</p>

<p align="center">
  <a href="https://elephc.dev"><strong>Official website</strong></a>
  &middot;
  <a href="https://github.com/illegalstudio/elephc/tree/main/docs">Documentation</a>
  &middot;
  <a href="https://github.com/illegalstudio/elephc/releases">Releases</a>
</p>

---

## Start here

- **[Install elephc](https://github.com/illegalstudio/elephc/blob/main/docs/getting-started/installation.md)** with elvm, then compile your first PHP program.
- **[Explore examples](https://github.com/illegalstudio/elephc/tree/main/examples)** to see the language and compiler extensions in action.
- **[Read the compiler source](https://github.com/illegalstudio/elephc)** to follow the path from PHP to native assembly.

The compiler is developed in **[illegalstudio/elephc](https://github.com/illegalstudio/elephc)**. This organization brings together its tooling and experiments.

## Projects

| Project | What you will find |
| --- | --- |
| [elephc](https://github.com/illegalstudio/elephc) | The PHP-to-native compiler, language documentation, examples, and releases. |
| [elvm](https://github.com/getelephc/elvm) | Install compiler versions side by side and pin a version per project. |
| [DOOM](https://github.com/getelephc/doom) | DOOM rendered in PHP and compiled to a native binary. A read-only mirror of the compiler's showcase. |
| [Laravel](https://github.com/getelephc/laravel) | Work in progress exploring Laravel compilation with elephc. |
| [Tempest](https://github.com/getelephc/tempest) | Work in progress exploring Tempest compilation with elephc. |

## PHP, running DOOM

<p align="center">
  <a href="https://github.com/getelephc/doom">
    <img src="https://raw.githubusercontent.com/getelephc/static/main/assets/doom/0.27.6/doom-readme-fluid.gif" alt="DOOM rendered in PHP and running as an elephc-compiled native binary" width="512">
  </a>
</p>

Explore the [DOOM showcase](https://github.com/getelephc/doom) for source, build instructions, and a walkthrough.

## Get involved

elephc is experimental and evolving. It compiles a supported subset of PHP, and the framework projects above are ongoing compatibility experiments.

Report compiler bugs and propose improvements in [elephc issues](https://github.com/illegalstudio/elephc/issues). For compiler and DOOM showcase contributions, start with the [contributing guide](https://github.com/illegalstudio/elephc/blob/main/CONTRIBUTING.md). For elvm, use its [own issue tracker](https://github.com/getelephc/elvm/issues).
