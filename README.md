**✨ Project Template Repository Guide ✨**

Hello Brain team! 👋

Here is a quick reminder on how to use our project template repository.
Let's make our code clean and consistent! 😃

**Usage Instructions 📚:**

1. **Install Ruff**: Run `pip install ruff`
2. **Lint your code**: Run `ruff check (--fix)`
3. **Format your code**: Run `ruff format`
4. **For vscode users**: Use ruff in vscode marketplace

Let's keep our code neat and tidy! 🧹

**Other Conventions 📝:**

1. **Type Annotations**: Please include type annotations for intuitive and clear codes (your editor may help you more!).
   Here's an example:

   ```python
    def add(a: int, b: int) -> int:
        return a + b
   ```

2. **Comments and Docstrings**: Make sure to add comments and docstrings.
   For example:

   ```python
    def greet(name: str) -> str:
        """Return a greeting message for the given name.

        Args:
            name (str): The name to greet.

        Returns:
            str: Greeting message.
        """
        return f"Hello, {name}!"
   ```

3. **Dependencies**: Record your dependencies in `requirements.txt` 📄

4. **README**: Write a clear and concise `README.md` file 📘

5. **Versioning**: Update the `CHANGELOG.md` when releasing new versions 📈

For any other guidelines, please refer to the [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html).
Let's adhere to these standards to maintain high-quality code. 🙏

Always appreciate for your dedicated effors and happy hacking! 💻✨

---

Copyright (c) 2024 maum.ai Brain
