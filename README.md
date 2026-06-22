# Baklib CMS — Jobs theme

A lightweight **recruiting portal / employer branding / job board** theme for Baklib-powered sites. It ships with structured job posts (location, employment type, salary, workplace mode), department/channel listing, online application forms, and Tailwind CSS–based styling.

Template Git URL: https://github.com/baklib-templates/jobs

---

## Features

Repository Layout

| Path                          | Purpose                                                         |
| ----------------------------- | --------------------------------------------------------------- |
| `templates/`                  | Page templates                                                  |
| `snippets/`                   | Partials / Snippets                                             |
| `layout/`                     | `theme.liquid` site shell                                       |
| `config/settings_schema.json` | Theme settings schema                                           |
| `locales/`                    | UI strings (`*.json`) and schema translations (`*.schema.json`) |
| `seeds/`                      | Sample site and pages (default **English**)                     |
| `assets/`                     | Built CSS/JS                                                    |
| `src/`                        | Source for Tailwind and JS                                      |

---

- **Home** (`templates/index.liquid`): homepage supporting job search, department/category navigation, job listings, and featured job recommendations.
- **Department / Channel** (`templates/channel.liquid`): lists all roles under a specific category, supporting multi-criteria filtering by location, employment type, and salary.
- **Job Post Page** (`templates/page.liquid`): displays role details (location, salary, employment type, workplace mode), skill tags, responsibilities, requirements, and an application form.
- **Search** (`templates/search.liquid`), **tag listing** (`templates/tag.liquid`).

---

## Preview

|             Home (Job Board)              |              Department / Channel              |
| :---------------------------------------: | :--------------------------------------------: |
| ![Home](assets/images/theme/en/index.png) | ![Channel](assets/images/theme/en/channel.png) |
|             **Job Post Page**             |             **Cover (Thumbnail)**              |
|  ![Job](assets/images/theme/en/page.png)  |   ![Cover](assets/images/theme/en/cover.png)   |

---

## Installation

Find "Jobs" in the Baklib template marketplace, click install, and it's done.

|                 1. Select and Install Theme                 |                      2. Add Channels and Jobs                      |
| :---------------------------------------------------------: | :----------------------------------------------------------------: |
| ![Install Theme](assets/images/guides/001_install_site.png) | ![Add Channels](assets/images/guides/002_add-channel-and-jobs.png) |
|                  **3. Job Post Settings**                   |                  **4. Home Page Configurations**                   |
| ![Job Settings](assets/images/guides/003_job-settings.png)  |   ![Index Settings](assets/images/guides/004_index-settings.png)   |

---

## Other Documents

- Chinese Overview: [README.zh-CN.md](./README.zh-CN.md)
- Theme Help: [www.baklib.ai/themes](https://www.baklib.ai/themes/jobs)
