# TextEditor (java) Modifications

This is a simple text editor. Using it as a starting point, it needs a bunch of functionality additions.

## Additions

Things to add:

- find/replace text implementation
- when you exit, you must NOT lose un-saved changes
- add a new window, scrollable, with some editor help documentation in it.
- implement Word Wrap (yeah, look it up)
- add a font panel, so you can change the font you edit in.
  - make sure not only new files are in the new font, but existing windows too.
- add a way to print the current file.
- add a way to set the page in portrait or landscape mode
- Make your About Dialog snazzy!

This text editor is kinda lit
Because we made it Taylor :)

CHRISTINE NOTES FOR YOU: the title was getting reset because the try-catches were outside of the
if statements. I changed it so the if statements are now on the outside and wrap the try-catches.
I also fixed a bug where if you cancel your save as, then we print to the console that the user 
close the dialog and didn't want to save - that prevents us from renaming our text file editor
jframe thing as "null TextFile Editor"