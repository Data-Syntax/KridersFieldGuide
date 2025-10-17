# DataSyntax Botanical Catalogs

This repository contains the LaTeX source files for a series of botanical-themed catalogs and field guides created for DataSyntax. Each catalog is designed with a specific aesthetic, from classic manuals to modern field guides, and built for high-quality PDF generation using LaTeX and the TikZ package for precise layout control.

## Table of Contents
1.  [Project Overview](#project-overview)
2.  [Catalogs in this Repository](#catalogs-in-this-repository)
    - [Catalog 000: The Rose Manual (DataSynstaix)](#catalog-000-rose)
    - [Catalog 002: The Daisy Family Field Guide (DataSyntax)](#catalog-001-daisy)
3.  [Prerequisites](#prerequisites)
4.  [Usage and Compilation](#usage-and-compilation)
5.  [Future Work & Request Queue](#future-work--request-queue)
6.  [License](#license)

## Project Overview

This project focuses on creating beautifully designed, single-subject botanical publications. The goal is to combine accurate, well-researched information with a strong, consistent visual identity. The layouts are created programmatically in LaTeX to ensure precision, scalability, and ease of modification.

---

## Catalogs in this Repository

### Catalog 000: Rose

-   **Description:** The first catalog in the series, designed with a classic, vintage "Owner's Manual" aesthetic. It features a serif font (EB Garamond), a parchment-like background, and detailed annotations pointing to different parts of the flower.
-   **Required Image:** `rose.png`

### Catalog 001: Daisy

-   **Description:** The second catalog, which establishes the modern "Field Guide" aesthetic for the DataSyntax brand. It uses a clean, minimalist layout with a modern sans-serif font (Roboto) and a professional color palette of Eggshell White and Charcoal. This issue focuses on the Asteraceae family, featuring the Zinnia and the Dahlia.
-   **Required Images:** `Zinnia.png`, `dahlia_whole.png`

---

## Prerequisites

To compile these LaTeX documents, you will need the following:

1.  **A LaTeX Distribution:** Overleaf
2.  **Compiler:** You **must** use either **XeLaTeX** or **LuaLaTeX**. These documents will not compile with pdfLaTeX due to the use of the `fontspec` package for custom system font loading.
3.  **Fonts:**
    -   **Roboto:** Used for Catalog 001. (Available on Google Fonts)
    -   **EB Garamond:** Used for Catalog 000. (Available on Google Fonts)
4.  **Image Files:** The required `.png` image files for each catalog must be present in the same directory as the `.tex` source file.

---

## Usage and Compilation

### Online Compilation (Overleaf)
1.  Create a new project in Overleaf.
2.  Upload the `.tex` file and the required image files.
3.  In the Overleaf Menu, go to **Compiler** and select **XeLaTeX**.
4.  Click "Recompile".

---

## Future Work & Request Queue

This section tracks pending requests for new catalog issues.

-   [ ] **New Catalog Issue:** Design and create a new catalog issue featuring the Asiatic dayflower (*Commelina communis*).
    -   *(1 request currently in the queue for this issue.)*

---

## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.
