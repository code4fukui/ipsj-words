# ipsj-words

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A collection of Japanese IT and computer science terms from the Information Processing Society of Japan (IPSJ), packaged as a CSV file with a searchable web application.

## Demo

[**IT Dictionary**](https://code4fukui.github.io/ipsj-words/)

A simple, single-page web application for searching and browsing the terminology list.

## Features

-   **Live Search:** Instantly search terms and definitions as you type.
-   **Interactive Definitions:** Keywords within definitions are hyperlinked, allowing you to jump to related terms.
-   **Random Term:** Discover new words with the "Random" (ランダム) button.
-   **Standalone:** A single HTML file with no server-side dependencies, using `IndexedCache.js` for fast local data access.

## Usage

1.  Visit the [demo site](https://code4fukui.github.io/ipsj-words/).
2.  Type a keyword into the search box to filter the list.
3.  Click the "Random" (ランダム) button to display a random term.
4.  Click on bolded keywords within a definition to search for that term.

## Data

The terminology data is provided as a single CSV file:
-   [`ipsj-words-ver.1.0_2024-4-10.csv`](ipsj-words-ver.1.0_2024-4-10.csv)

The file contains the following primary fields:
-   `用語` (Term): The Japanese term. May include variations separated by `|`.
-   `説明` (Definition): The definition of the term.

Additional columns provide metadata such as category, codes, and usage statistics in various textbooks.

The data is licensed under CC 4.0 BY-SA from the [IPSJ Information Entrance Examination Committee - Information Science Textbook Terminology List](https://sites.google.com/a.ipsj.or.jp/ipsjjn/wordlist).

## License

MIT License — see [LICENSE](LICENSE).