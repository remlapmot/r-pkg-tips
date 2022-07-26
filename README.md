# Tips for coding R packages

Rendered at https://remlapmot.github.io/r-pkg-tips/

To build the website either

- open the project in RStudio, go to the *Build* pane and click *Build Website*
- or, run in R

    ```r
    # install.packages('quarto')
    quarto::quarto_render()
    ```

Or at the command line

    ```bash
    quarto render
    ```

When editing the project preview with

    ```r
    quarto::quarto_preview()
    ```

or 

    ```bash
    quarto preview
    ```
And stop the process with <kbd>Ctrl</kbd>+<kbd>C</kbd> or with

    ```r
    quarto::quarto_preview_stop()
    ```
