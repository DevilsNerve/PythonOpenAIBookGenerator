# OpenAI Book Writer

OpenAI Book Writer is a Python utility that leverages the OpenAI GPT API to generate books on specified themes.

## Features

- Define your book's title and theme.
- Set the desired number of chapters and words per chapter.
- The script automatically structures the content into chapters and saves it as a `.txt` file.

## Prerequisites

- An OpenAI account with API access.
- Python 3.x

## Setup

1. Clone the repository:

```bash
git clone https://github.com/DevilsNerve/PythonOpenAIBookGenerator.git
```

2. Install the required packages:

```bash
pip install openai
```

3. Replace `'YOUR_OPENAI_API_KEY'` in the script with your actual OpenAI API key.

## Usage

You can generate a book by calling the `write_book` function:

```python
write_book("Title of the Book", "Theme of the Book", num_chapters=5, words_per_chapter=2000)
```

For example:

```python
write_book("My AI Generated Book", "The Future of Technology", num_chapters=5, words_per_chapter=2000)
```

This will generate a book titled "My AI Generated Book" with a theme focused on "The Future of Technology", containing 5 chapters and approximately 2000 words per chapter.

## Warning

Generating a book will result in multiple API calls to OpenAI. Please be cautious about API rate limits and costs associated with generating large amounts of content.

## Contribution

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
