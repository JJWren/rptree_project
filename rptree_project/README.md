# Directions

1. Open Terminal
2. Change Directory to program folder's location (location of `tree.py`)
3. To generically run with defaults (the current directory will be used), type:
    1. `python tree.py`
4. To run with params, see `Parameters`

# Parameters

-   `-v`, `--version` show the current version information and exit the application.

    ```
    $ python tree.py -v
    RP Tree v0.1.0
    ```

-   `-h`, `--help` show help and usage messages.
-   `-d`, `--dir-only` generate a directory-only tree and print it into the screen.
-   `-o`, `--output-to-markdown` generate a tree and save it to a file in markdown format.

    ```
    $ python tree.py ../hello -o output_file.md
    ```

```
The above outputs the tree structure for ../hello to output_file.md (Markdown file)
```
