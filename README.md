# Kysely Snippets

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/imgildev.vscode-kysely-snippets?style=for-the-badge&label=VS%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-kysely-snippets)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/imgildev.vscode-kysely-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-kysely-snippets)
[![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/imgildev.vscode-kysely-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-kysely-snippets)
[![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/imgildev.vscode-kysely-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-kysely-snippets&ssr=false#review-details)
[![GitHub Repo stars](https://img.shields.io/github/stars/ManuelGil/vscode-kysely-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-kysely-snippets)
[![GitHub license](https://img.shields.io/github/license/ManuelGil/vscode-kysely-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-kysely-snippets/blob/main/LICENSE)

> A Visual Studio Code extension offering a comprehensive set of snippets for Kysely ORM, accelerating schema and query builder development.

## Overview

Kysely Snippets provides:

- **Dialect & Database Initialization**: Snippets for creating `PostgresDialect`, `MysqlDialect`, `SqliteDialect`, and `Database` instances.
- **Schema Utilities**: Shortcuts for `Generated`, `ColumnType`, `Selectable`, `Insertable`, and `Updateable` types.
- **Migration Helpers**: Snippets for `createTable`, `createIndex`, and `Migrator`.
- **Query Builder Methods**: Common operations (`selectFrom`, `insertInto`, `updateTable`, `deleteFrom`).

Rather than memorizing long method names, insert them with a brief prefix and press **Tab** or **Enter** to expand.

## Requirements

- Visual Studio Code 1.46.0 or later (compatible with VSCodium, WindSurf, Cursor, etc.)

## Installation

1. Open **Visual Studio Code**.
2. Open the **Extensions** view (`Ctrl+Shift+X` on Windows/Linux or `⌘+Shift+X` on macOS).
3. Search for **Kysely Snippets** or install from the [Marketplace](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-kysely-snippets).
4. Click **Install** and reload the editor if prompted.

## Usage

1. Open a JavaScript or TypeScript file in your Kysely project.
2. Type a snippet prefix such as `kysely_select_from` and press **Tab** or **Enter** to expand.

### Snippets

| Snippet                   | Purpose             |
| ------------------------- | ------------------- |
| kysely_new_dialect_pg     | new PostgresDialect |
| kysely_new_dialect_mysql  | new MysqlDialect    |
| kysely_new_dialect_mssql  | new MssqlDialect    |
| kysely_new_dialect_sqlite | new SqliteDialect   |
| kysely_new_db             | new Database        |
| kysely_new_migrator       | new Migrator        |
| kysely_id_generated       | Generated           |
| kysely_column_type        | ColumnType          |
| kysely_selectable         | Selectable          |
| kysely_insertable         | Insertable          |
| kysely_updateable         | Updateable          |
| kysely_create_table       | createTable         |
| kysely_create_index       | createIndex         |
| kysely_insert_into        | insertInto          |
| kysely_select_from        | selectFrom          |
| kysely_update_table       | updateTable         |
| kysely_delete_from        | deleteFrom          |

## Contributing

Contributions to the Kysely Snippets are welcome and appreciated. To contribute:

1. Fork the [GitHub repository](https://github.com/ManuelGil/vscode-kysely-snippets).
2. Create a new branch for your feature or fix:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Make your changes, commit them, and push to your fork.
4. Submit a Pull Request targeting the `main` branch.

Before contributing, please review the [Contribution Guidelines](https://github.com/ManuelGil/vscode-kysely-snippets/blob/main/CONTRIBUTING.md) for coding standards, testing, and commit message conventions. If you encounter a bug or wish to request a new feature, please open an Issue.

## Changelog

For a complete list of changes, see the [CHANGELOG.md](https://github.com/ManuelGil/vscode-kysely-snippets/blob/main/CHANGELOG.md).

## Authors

- **Manuel Gil** - _Owner_ - [@ManuelGil](https://github.com/ManuelGil)

For a complete list of contributors, please refer to the [contributors](https://github.com/ManuelGil/vscode-kysely-snippets/contributors) page.

## Follow Me

- **GitHub**: [![GitHub followers](https://img.shields.io/github/followers/ManuelGil?style=for-the-badge\&logo=github)](https://github.com/ManuelGil)
- **X (formerly Twitter)**: [![X Follow](https://img.shields.io/twitter/follow/imgildev?style=for-the-badge\&logo=x)](https://twitter.com/imgildev)

## Other Extensions

- **[Auto Barrel](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-auto-barrel)**
  Automatically generates and maintains barrel (`index.ts`) files for your TypeScript projects.

- **[Angular File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-angular-generator)**
  Generates boilerplate and navigates your Angular (9→20+) project from within the editor, with commands for components, services, directives, modules, pipes, guards, reactive snippets, and JSON2TS transformations.

- **[NestJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-generator)**
  Simplifies creation of controllers, services, modules, and more for NestJS projects, with custom commands and Swagger snippets.

- **[NestJS Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)**
  Ready-to-use code patterns for creating controllers, services, modules, DTOs, filters, interceptors, and more in NestJS.

- **[T3 Stack / NextJS / ReactJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nextjs-generator)**
  Automates file creation (components, pages, hooks, API routes, etc.) in T3 Stack (Next.js, React) projects and can start your dev server from VSCode.

- **[Drizzle ORM Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-drizzle-snippets)**
  Collection of code snippets to speed up Drizzle ORM usage, defines schemas, migrations, and common database operations in TypeScript/JavaScript.

- **[CodeIgniter 4 Spark](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-spark)**
  Scaffolds controllers, models, migrations, libraries, and CLI commands in CodeIgniter 4 projects using Spark, directly from the editor.

- **[CodeIgniter 4 Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-snippets)**
  Snippets for accelerating development with CodeIgniter 4, including controllers, models, validations, and more.

- **[CodeIgniter 4 Shield Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets)**
  Snippets tailored to CodeIgniter 4 Shield for faster authentication and security-related code.

- **[Mustache Template Engine - Snippets & Autocomplete](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-mustache-snippets)**
  Snippets and autocomplete support for Mustache templates, making HTML templating faster and more reliable.

## Recommended Browser Extension

For developers who work with `.vsix` files for offline installations or distribution, the complementary [**One-Click VSIX**](https://chromewebstore.google.com/detail/imojppdbcecfpeafjagncfplelddhigc?utm_source=item-share-cb) extension is recommended, available for both Chrome and Firefox.

> **One-Click VSIX** integrates a direct "Download Extension" button into each VSCode Marketplace page, ensuring the file is saved with the `.vsix` extension, even if the server provides a `.zip` archive. This simplifies the process of installing or sharing extensions offline by eliminating the need for manual file renaming.

- [Get One-Click VSIX for Chrome &rarr;](https://chromewebstore.google.com/detail/imojppdbcecfpeafjagncfplelddhigc?utm_source=item-share-cb)
- [Get One-Click VSIX for Firefox &rarr;](https://addons.mozilla.org/es-ES/firefox/addon/one-click-vsix/)

## License

This project is licensed under the **MIT License**. See the [LICENSE](https://github.com/ManuelGil/vscode-kysely-snippets/blob/main/LICENSE) file for full details.
