
# Release 0.1.0

## Added on 22.12.2023:
- C: Fixed an issue, when user tried to copy a file to directory with a new name.
- P: Program was rewritten
- PERM: Fixed issues with verbose mode still being enabled while it shouldn't
- RUSH: Added an extremely early shell for CarrotOS

## Added on 23.12.2023:
- C: Fixed directory to directory copying
- RUSH: Can understand some built-in commands and execute commands 

# Release 0.1.1

## Added on 28.12.2023

- JUNK: Ability to overwrite files with zeroes or random bytes
- JUNK: Ability to create files with zeroes or random bytes of desired size
- JUNK: Verbose mode

# Release 0.2.0 (Planned)

## Added on 28.12.2023

- RUSH: Support for keyboard shortcuts
- RUSH: Separation of some code from RUSH to libinput

## Added on 29.12.2023

- L: Less spaghetti code
- C: Heavily rewritten to fix many bugs and ditch spaghetti code
- M: Same as for the previous program since "M" does practically the same job as "C"

## Waiting features:

- RD, RF, JUNK: Migrate ask() to libinput
- RUSH: Run files (scripts) passed as arguments from CLI
- RUSH: Ability to view and modify variables
- RUSH: Restricted shell mode
- RUSH: File mode
- RUSH: Sleep/wait command
- RUSH: History