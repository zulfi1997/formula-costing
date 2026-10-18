# Compounding Formula Costing

A single-page tool for costing compounding formulas, planning production and checking raw-material stock.

**Open it:** https://zulfi1997.github.io/formula-costing/

## What it does
1. **Inventory**: upload the Item Valuation Summary (Excel/CSV). Avg Cost per UOM, On Hand and categories are read automatically.
2. **Formulas**: upload a master formula record (Excel, every formula block in every sheet), a Word (.docx) or PDF formula, or paste one. Scanned PDFs (images) cannot be read.
3. **Matching**: each ingredient is matched to the closest inventory item, with confidence and alternatives, or to an intermediate formula (e.g. acetate buffer → INT-06). Corrections are remembered.
4. **Provisions & pricing**: overage, labour, QC, overheads, markup or target margin.
5. **Production plan & stock check**: choose formulas (or all at once) and quantities; get total raw materials required versus On Hand, with shortfalls and an Excel purchase list. Intermediates (buffers, stock solutions) use ready-made stock first, then are expanded into their own raw materials.
6. **Formula review**: critical gaps, warnings and recommendations for every formula, plus item-master clean-up lists.

## Privacy
Files are read in the browser only and never uploaded. Matches, provisions and plans are saved in each user's own browser (localStorage).
