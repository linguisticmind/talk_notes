# movies2anki tweaks

Video tutorial: https://www.youtube.com/watch?v=YOh_s6LBqto<br>
movies2anki on AnkiWeb: https://ankiweb.net/shared/info/939347702

movies2anki id: `939347702`

## Setting an mpv profile

Add line<br>
`args += ["--profile=movies2anki"]`<br>
before line<br>
`cmd = [mpv_executable] + args + [fullpath]` (around line 239)<br>
in `player.py` file.

[Video demonstration](https://www.youtube.com/watch?v=YOh_s6LBqto&t=24m17s "Setting mpv profile")

## Changing 'Generate Video Cards' shortcut

Change line<br>
`action.setShortcut(QKeySequence("Ctrl+M"))` (around line 2016)<br>
to<br>
`action.setShortcut(QKeySequence("Ctrl+Alt+M"))` (insert desired key combination)<br>
in `movies2anki.py` file.

[Video demonstration](https://www.youtube.com/watch?v=YOh_s6LBqto&t=26m23s "Changing 'Generate Video Cards' shortcut")

## Changing model name

Search the entire code of movies2anki for<br>
`movies2anki (add-on)`,<br>
and replace it with `Main` (or some other name you prefer).

[Video demonstration](https://www.youtube.com/watch?v=YOh_s6LBqto&t=29m5s "Changing model name")

## Getting the note types whose name *starts with* `Main` to play as well

Search the entire code of movies2anki for<br>
` == "Main"` (There should be a space before the `==`! No way to display it on GitHub),<br>
and replace it with<br>
`.startswith("Main")` (substitute a different name if you prefer).

[Video demonstration](https://www.youtube.com/watch?v=YOh_s6LBqto&t=35m34s "Making it so that note types *starting with* 'Main' also play")
