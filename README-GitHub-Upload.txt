KEEGAN QUEST - GITHUB WEBSITE UPLOAD

This folder is specially prepared for GitHub's browser uploader.

1. Upload every file in this folder to the ROOT of your GitHub repository.
2. Do not upload this enclosing folder itself.
3. Keep all four split files:
   - index.wasm.part1
   - index.wasm.part2
   - index.pck.part1
   - index.pck.part2
4. Enable GitHub Pages from main / root.
5. Do not rename the part files.

The large Godot files were split because GitHub's browser uploader rejects
individual files over 25 MiB. The patched index.html joins the parts in the
browser before starting the game. No command line is required.
