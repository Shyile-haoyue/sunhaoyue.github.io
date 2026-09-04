# Flat GitHub Pages version

Upload every file from `phd-homepage-flat` directly to the repository root. The package intentionally contains no folders.

Important: make sure `.nojekyll` is present in the repository root. If your computer hides dotfiles, create it on GitHub using **Add file → Create new file**, enter `.nojekyll` as the filename, add any short line of text, and commit it.

The new `index.html` becomes the homepage. Existing Markdown and Jekyll files may remain in the repository, but they are ignored when `.nojekyll` is present.

