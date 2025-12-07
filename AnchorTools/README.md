# Anchor Tools

A Glyphs 3 plugin to help you **inspect, harmonize and autofill anchor points** — making anchor management easier and more consistent across glyphs and masters.

## ✅ Features (v0.2)

- **Inspect anchors** — scan selected glyphs across masters, and detect:  
  - Missing anchors  
  - Extra anchors  
  - Anchor-position outliers (when anchors are inconsistent across masters)  
- **Harmonize anchors** — align anchors across masters for selected glyphs, based on a default anchor set and averaged positions.  
- **Auto-fill anchors** — automatically add missing anchors for selected glyphs using built-in presets.  
- **Batch processing** — works on multiple glyphs at once, saving you from manual anchor-by-anchor edits.  
- **Clean UI** — a tidy, easy-to-use panel with three tabs (Inspect / Harmonize / Auto Fill). Accessible from the “Glyph” menu or quick-command menu entries.

## 📥 Installation & Update

Once published in the Glyphs Plugin Manager:

1. Open Glyphs 3 → go to **Window → Plugin Manager**.  
2. Search for **“Anchor Tools”** and click **Install**.  
3. To update: after a new version is released, use **Plugin Manager → Update**.

No manual copying of files is needed — installation and updates are handled by Glyphs itself.
![](./img/main_panel.png)

## 🛠️ Usage Guide

1. Open your font in Glyphs 3.  
2. Select one or more glyphs to work on.  
3. From the menu **Glyph → Anchor Tools…** open the plugin panel.  
4. Choose the appropriate tab:  
   - **Inspect** → click **Run Inspect** to analyze anchor status across masters.  
   - **Harmonize** → click **Run Harmonize** to align anchors.  
   - **Auto Fill** → click **Run Auto Fill** to add missing anchors per presets.  
5. Review the summary and results; make manual corrections if needed.

## ⚠️ Please Note (Limitations & Best Practices)

- The plugin uses a *default anchor set and preset rules*. If your font uses custom anchor names or non-standard conventions, results may not be accurate.  
- Auto-Fill may not perfectly match all anchor-naming conventions. Always perform an **Inspect** after Auto-Fill and manually verify results.  
- The plugin modifies your font masters. **Always keep a backup copy** of your font before running batch operations.  
- For large fonts or many masters, operations may take noticeable time — please be patient while processing completes.

## 📄 License & Support

- This plugin is provided “as-is” with no liability. Use at your own risk.  
- For bug reports or feature requests, please use the support channel provided in the Plugin Manager entry (or contact the developer).  
- By installing this plugin through Glyphs Plugin Manager, you agree to the above terms.