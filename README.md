# Website Content Summarizer with OpenAI

This Python script fetches and parses the content of any given html webpage, cleans it of irrelevant elements (scripts, styles, images, inputs), and generates a concise, navigation-free summary using OpenAI's Chat Completions API.

---

## Features
- **Web scraping with BeautifulSoup** – Extracts the main text content from a webpage.
- **Automatic cleaning** – Removes common irrelevant HTML elements such as `<script>`, `<style>`, `<img>`, and `<input>`.
- **AI-powered summarization** – Uses OpenAI's GPT model (`gpt-4o-mini` by default) to produce short, meaningful summaries.
- **Markdown output** – Displays the result in Markdown format for easy reading (Jupyter-friendly).
- **Customizable system prompt** – Allows tuning of summarization style.

---

