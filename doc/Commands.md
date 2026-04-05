## TODO Helpful commands to memorize
### Visual block mode (for making a comment along a selection, or inserting something across a vertical block of text)
[nvim docs](https://neovim.io/doc/user/visual/#visual-block)
1. Go to the first line you want to comment, press CtrlV. This will put the editor in the VISUAL BLOCK mode.
2. Select until the last line
3. Press Shift+I, which will put the editor in INSERT mode. Insert whatever you need to insert, keeping in mind only the top line will visually look different.
4. Press Esc (give it a second), and it will insert whatever you typed in INSERT mode.
