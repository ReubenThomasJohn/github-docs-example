# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* to copy, paste, and share code. A good __Cloud Engineer__ uses Codeblocks whenever possible.

- In order to create code blocks in markdown, use three backticks `(```)`
- Not to be confused with quotation marks `(''')`
- Add the name of the language/extension after the first three quotation marks for syntax highlighting `(```python3)`

```python3
class Book:
    def __init__(self, title, author, publication_year, ISBN):
        self.title = title
        self.author = author
        self.publication_year = publication_year
        self.ISBN = ISBN

    def __str__(self):
        return f"Title: {self.title}\nAuthor: {self.author}\nPublication Year: {self.publication_year}\nISBN: {self.ISBN}"

    def display_info(self):
        print(self.__str__())

# Usage example:
book1 = Book("The Great Gatsby", "F. Scott Fitzgerald", 1925, "978-0743273565")
book2 = Book("To Kill a Mockingbird", "Harper Lee", 1960, "978-0061120084")

# Display book information
print("Book 1 Information:")
book1.display_info()

print("\nBook 2 Information:")
book2.display_info()
```

- Make note of where the backtick button is located.
- May vary based on keyboard layout

<img width="200px" alt="backtick key" src="https://github.com/ReubenThomasJohn/github-docs-example/assets/72449974/45778ca7-3f53-4ab6-a661-ecbd419e8a0e">


Paste in errors logged onto the console, and use `bash` for syntax highlighting.

```bash
Traceback (most recent call last):
  File "example.py", line 3, in <module>
    result = 10 / 0
ZeroDivisionError: division by zero
```
> Here is an example of  using a code block for an error that appears in `bash`

## Step 3 - Use Github Flavoured Task Lists <sup>1</sup>

Github extends markdown to have a list where you can check off items.

- [x] Step 1
- [ ] Step 2
- [ ] Step 3

## Step 4 - Use Emojis <sup>2</sup> (Optional)
Github Flavoured Markdown (GFM) allows emoji shortcodes.
Here are some examples:

| Name  | Shortcode | Emoji |
| ----- | ------ | ------ |
| Cloud  | `:cloud:`  | :cloud: |
| Cloud with lightning  | `🌩:cloud_with_lightning`  | 🌩️ |

## Step 5 - How to create a table
```md
| Name  | Shortcode | Emoji |
| ------------- | ------------- | ------------- |
| Cloud  | `:cloud:`  | :cloud: |
| Cloud with lighting  | `🌩:cloud_with_lightning`  | 🌩️ |
```

## References

- [Github Flavoured Markdown Spec](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) <sup>1</sup>
- [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) <sup>2</sup>
- [Using Tables](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables)
