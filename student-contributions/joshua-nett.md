# Joshua Nett

## Something I Have Learned About Git

I have learned a lot about using Git from the command line on both Windows and Linux. Before this, I relied more on GUI tools such as the GitHub app.

## Helpful Git Command

```bash
# Linux
git config --global core.editor "subl -n -w"
```

```bash
# Windows
git config --global core.editor "'%ProgramFiles%\Sublime Text\sublime_text.exe' -n -w"
```
These commands change the default editor used for commit messages. This is especially useful when you want to open a text editor instead of the terminal editor.

You can swap out Sublime Text for another editor if you prefer. The `-n` and `-w` flags are Sublime Text options, and other editors may use different switches.
