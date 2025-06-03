````markdown
News Crawler 📰

A simple Python-based news crawler that fetches news data and outputs it in a structured format.

## Features

- Crawls and extracts news articles
- Outputs data for further processing
- Converts `.docx` to `.md` for better compatibility on Linux systems

## Requirements

- Python 3.8+
- `venv` for isolated Python environments
- Dependencies listed in `requirements.txt`

## Installation & Usage

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Nyxro0t/news_crawler.git
   cd news_crawler
````

2. **Create and Activate Virtual Environment**

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Crawler**

   ```bash
   python3 news.py
   ```

5. **Convert Output (Optional)**
   If the crawler outputs a `.docx` file and you're on Linux, you can convert it to `.md` using `pandoc`:

   ```bash
   pandoc output.docx -o output.md
   ```

## Notes

* `.docx` files may not open easily in some Linux environments, so converting to Markdown (`.md`) is recommended for easier readability and version control.
* Make sure `pandoc` is installed:

  ```bash
  sudo apt install pandoc
  ```

## License

This project is licensed under the MIT License.

---

```

Let me know if you'd like badges, usage examples, or an architecture diagram added.
```
