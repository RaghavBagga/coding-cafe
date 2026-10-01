# Coding Café Lab 1 — Notes

1. `pwd` printed `/home/ragha`.

2. `ls -a` showed hidden files and folders beginning with a dot, including `.bashrc`, `.config`, and `.cache`, which plain `ls` did not show.

3. For `coding-cafe`, the `d` at the beginning of `drwxr-xr-x` means it is a directory. The remaining characters show read, write, and execute permissions for the owner, group, and other users.

4. `ls coding-cafe/week02` works because I am in my home directory and `coding-cafe/week02` describes a location starting from there. It is a relative path because it does not start with `/`.

5. `mv` first moved `README-backup.md` into the `week01` folder. It then renamed the file from `README-backup.md` to `old-readme.md`.

6. My PATH contains 20 folders. The shell searches these folders in order when I type a command.

7. Python lives at `/usr/bin/python3`. On this Ubuntu setup, the command is called `python3` rather than `python`.

8. I was unable to compare with a classmate because I am completing the lab remotely. Python paths can differ based on the operating system, Python version, or installation method.

9. The shell said `pyton: command not found`. It searched the folders in my PATH for a command called `pyton` but could not find one because the command name was misspelled.

10. `.venv` did not appear with plain `ls` because names beginning with a dot are hidden in Linux. `ls -a` shows hidden files and folders.

11. `(.venv)` appeared at the beginning of my prompt. This shows that the virtual environment is active.

12. It is not the same path as Q7: Python now points to `/home/ragha/coding-cafe/.venv/bin/python`. Activating the environment put its `bin` folder at the beginning of PATH, so this virtual environment's Python is found first.

13. The second list included `requests 2.34.2`, which was not in the first list. It also included supporting packages such as `certifi`, `charset-normalizer`, `idna`, and `urllib3`.

14. After deactivating the environment, `python` no longer points to a command. The normal system Python is available as `python3` at `/usr/bin/python3`.

15. The `-R` (or `--recursive`) option makes `ls` show the contents of subdirectories as well as the current directory.

16. Ctrl+C interrupts the currently running command or program. Ctrl+D sends an end-of-input signal, which closes the Python interpreter.
