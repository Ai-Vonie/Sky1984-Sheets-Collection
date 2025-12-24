# [Sky1984 Sheets Collection](https://api.github.com/repos/Ai-Vonie/Sky1984-Sheets-Collection/releases)
🌍 Read in: **English** *∙ [Русский](README_ru.md)*

**Sky1984 Sheets Collection** is an extensive library of music sheets collected to simplify the search for specific compositions in one place. These sheets are designed for playing on in-game instruments in **Sky: Children of the Light** and for use on the *[Sky Music Nightly](https://sky-music-nightly.pages.dev/)* site.

> ⚠️ **Attention!**
> This collection is not complete or final. It is recommended to check other sources and libraries for updates, as the content of this repository may be outdated or irrelevant compared to them.

# 🔍 How to Properly Search for Sheets

For an effective search of the desired composition, try to follow these recommendations:
*   **Use main keywords:** Enter only keywords or the significant part of the song title, as well as the author's nickname.
*   **Avoid clutter:** Exclude **stop words** (articles, conjunctions, prepositions) and specific symbols from your query.

The repository search works in two modes:
1.  **[By file name](https://docs.github.com/search-github/searching-on-github/finding-files-on-github)** — press `t` or click the button (Go to file) to start searching in the file quick jump menu.
2.  **[By file content](https://docs.github.com/search-github/github-code-search/using-github-code-search)** — press `/` or click the search field above (Type `/` to search) to activate [global code search in this repository](https://github.com/search?q=repo%3AAi-Vonie%2FSky1984-Sheets-Collection%20&type=code).

> ⚠️ **Attention!**
> To use code search (file content), you must **be logged into your GitHub account**.

It is recommended to read the documentation on [code search limitations](https://docs.github.com/search-github/github-code-search/about-github-code-search#limitations) and [special query syntax](https://docs.github.com/search-github/github-code-search/understanding-github-code-search-syntax) to understand the capabilities and technical constraints.

# 💾 How to Download

You can download individual files, specific folders, or the entire repository at once.

### 1. Downloading an Individual File
Go to the page of the desired file and choose a convenient method:
*   **Download file:** Click the icon (**Download raw file**) in the upper right corner above the file code.
*   **Copy content:** Click the icon (**Copy raw file**) to copy the text to the clipboard.
*   **Via Raw:** Click the **Raw** button, then press `Ctrl + S` (Windows) or `Cmd + S` (macOS) to save the file.

### 2. Downloading a Specific Folder
GitHub does not allow downloading individual folders by default. Use [Download Directory](https://github.com/download-directory/download-directory.github.io) for this:
1.  Open the desired folder in this repository.
2.  Copy the link (URL) from the browser address bar.
3.  Go to [download-directory.github.io](https://download-directory.github.io/).
4.  Paste the link into the input field and press `Enter`. The folder will download as a ZIP archive.

### 3. Downloading the Entire Repository
To get a full local copy of the library:
1.  Go to the main repository page.
2.  Click the green **`<> Code`** button.
3.  Select [**`Download ZIP`**](https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/archive/refs/heads/master.zip) from the dropdown menu.

Can also download a specific folder or the entire repository from the [**Releases**](https://github.com/Ai-Vonie/Sky1984-Sheets-Collection/releases) tab.

# 💭 Why?

The idea to create this collection came up two years ago, but back then I switched to other games, where I also continued my path as a musical bard.

When I had some free time in FFXIV, I decided to just do it, because existing alternatives and other library options didn't satisfy me with their implementation or organizational approach for using these sheets in other games. The repository itself was assembled in a couple of evenings.

### ⚙️ Technical Details
Initially, ±59,457 files were collected. The final collection is the result where duplicates were removed, and files with the most "quality" internal content and filename were retained.

A custom algorithm was used for filtering with the following logic:
1.  **Exact Duplicates:** Comparison by SHA-256 file hash.
2.  **Structural Duplicates:** Analysis of JSON metadata content.
3.  **Fuzzy Matching:** Comparison of note sequences within the same BPM group to identify similar arrangements (with a similarity threshold of ~80%).

> **Note:** Some files were allowed into the repository if song variations were encountered (*Easy/Hard*, *V1/V2*, and other possible options).
