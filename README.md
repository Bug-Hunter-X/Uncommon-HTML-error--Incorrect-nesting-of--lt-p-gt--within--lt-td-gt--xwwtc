# Uncommon HTML Error: Incorrect Paragraph Nesting in Table Cell

This repository demonstrates an uncommon HTML error involving incorrect nesting of a paragraph (`&lt;p&gt;`) element inside a table cell (`&lt;td&gt;`).  While browsers often handle this, it can cause unexpected rendering and styling issues across different browsers and is considered bad practice.

The `bug.html` file shows the incorrect code, and `bugSolution.html` provides the corrected version.

**Problem:**
Nesting block-level elements like paragraphs directly inside table cells can cause layout problems.  It's generally recommended to avoid this.

**Solution:**
The best practice is to keep the content within the table cells simple.  If more complex structuring is needed, consider using divs or spans within the cells.