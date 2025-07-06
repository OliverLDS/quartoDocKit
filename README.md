# quartoDocKit

**Note: This package was originally created for personal use under the name `RmarkdownWordTemplates`, and has not been actively maintained in recent years.**

It began as a collection of Microsoft Word `.docx` templates for use with R Markdown documents, primarily focused on academic or report-style formatting. These templates were useful in customizing the appearance of Word output generated via `rmarkdown::render()`.

---

## ⚠️ Current Status

Since its creation, the R Markdown ecosystem has evolved, and **RStudio now defaults to Quarto**, which I personally find **more functional and bug-free** after switching. As a result, I have renamed the package to **`quartoDocKit`** and plan to **update it to support Quarto** and expand its purpose in the following ways:

---

## 🛠 Planned Improvements

This package will eventually evolve into a **Quarto-compatible document toolkit** with the following features:

* ✅ **Support for Quarto**: Updated templates compatible with `.qmd` files.
* 🗂 **More templates**: Covering academic, business, and creative writing structures.
* ✍️ **Function-based rendering**: Generate full documents using R functions.
* 📊 **Integrated `ggplot2` styling**: Auto-inserted charts and formatted narratives.
* 🤖 **LLM-assisted writing**: Utilities to help draft, revise, and style documents using large language models (e.g., OpenAI).
* 📚 **Prebuilt writing structures**: For reports, essays, memos, slides, etc.

---

## ⏳ Timeline

There is **no fixed update schedule**, but I will work on improvements **as time permits**. The goal is to make this a more robust, practical toolkit for document automation, writing assistance, and reproducible reporting.

---

## 📁 Legacy Usage (R Markdown)

To use existing templates in classic R Markdown:

```yaml
output:
  word_document:
    reference_docx: "your_template.docx"
```

---

## 📬 Contributions

Not actively accepting pull requests yet, but feel free to fork or follow if you're interested in document generation tools with R + Quarto.

---

## License

MIT
