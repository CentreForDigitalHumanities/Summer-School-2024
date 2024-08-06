## Why does Python use snake case?

According to [this post on Quora](https://www.quora.com/Why-does-Python-use-snake_case-as-a-convention) Python uses `snake_case` as a convention for naming variables, functions, and other identifiers for a few reasons:

1. **Readability**: Snake_case is considered more readable than other naming conventions like camelCase or PascalCase. In snake_case, words are separated by underscores, making it easier to read and understand multi-word identifiers.
2. **Consistency**: Guido van Rossum, the creator of Python, chose snake_case as the naming convention for the Python language early on. Consistency in naming conventions is important for code readability and maintainability, especially in larger codebases or when working with multiple developers.
3. **Compatibility**: Python's standard library and many popular libraries and frameworks follow the snake_case convention. By adhering to the established convention, developers can write code that is consistent with existing codebases and community standards.
4. **PEP 8**: PEP 8 is the style guide for Python code. It recommends the use of snake_case for variable names, function names, and module names. Following PEP 8 helps maintain a consistent style across Python projects and improves code readability for developers.

Overall, using snake_case as a naming convention in Python helps improve code readability, maintainability, and consistency within the Python community.

## What is a good example of usage for slicing?
- If you want to grab an ID from a Tweet URL\
Example: `1808774347701559757` from https://x.com/data_school/status/1808774347701559757

## Where do I find documentation on what I can all do with Python?

1. There is extensive [documentation](docs\documentation.md) on Python, Anaconda, Jupyter Lab and IPython.
2. Depending on what you're planning to do, there are third-party libraries to extend Python's capabilities. For example:
    - `NumPy`: Numerical computing.
    - `Pandas`: Data manipulation and analysis.
    - `Matplotlib` or `Seaborn`: Data visualization.
    - `requests` or `httpx`: HTTP requests.
    - `BeautifulSoup`: Web scraping.
    - `TensorFlow` or `PyTorch`: Machine learning and deep learning.
3. If you have a specific idea of what you would like to do, formulate a search query in a form like `How to X in Python?` and put that into a search engine. It is very likey that you will end up on an online community for developers such as StackOverflow, where solutions are discussed.
4. AI assistants like ChatGPT and GitHub Copilot can nowadays be really helpful in explaining error messages and alike.