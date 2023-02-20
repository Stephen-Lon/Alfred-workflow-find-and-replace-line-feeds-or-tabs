# Alfred-workflow-find-and-replace-line-feeds-or-tabs

# Warning
Because of the limitations of regular expressions (or my knowledge of them!) use this workflow with care. *Make sure you have a backup of your document before letting this workflow loose on the document (or copy to clipboard at the end and check the results before overwriting)*.

The workflow works well for its basic operations but may have unforeseen results if, for example, you're trying to replace a whole sequence of line feeds or tabs (where you may end up with more of either than you expected).

# What it does

This Alffed workflow is a `Universal Action` which acts on selected text (using your `Universal Action` shortcut key). You can choose to find any of the following:
- single line feeds;
- double line feeds;
- single tabs; or
- double tabs.

You can then replace your selection with any of:

- single line feeds;
- double line feeds;
- single tabs;
- double tabs;
- a space; or
- nothing (effectively deleting what you chose to find).

(What you see in the replace list excludes what you selected in the find list.)

The workflow gives you the options of:
- overwriting the original text with the result (the default); or
- copying the resulting text to the clipboard.

# Note

I had thought of combining this with my [Find and replace text workflow](https://alfred.app/workflows/stephenc/find-and-replace-text/) but felt that made the latter unduly cumbersome. Use that workflow for text replacements and this one for replacements of non-printing characters.
