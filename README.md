# BuildProject
The `build-project` command is an alias for a MacOS solution for building and populating a skeletal structure of files and directories for differnet kinds of development projects.

# Version History

## 0.1
- Define the project
- Define the desired outcome
- Propose a procedure

# Desired Outcome
Upon running `build-project <required-project-name> <optional-project-type> <optional-project-location>`, a directory will be built of name `project-name`, with files and subdirectories which adhere to a default format or the format of the `project-type`.

# Project Requirements
`build-project` should be able to do the following:
1. Build a directory in a default location or one that matches `project-location`.
2. Add files and subdirectories based on a default format or one corresponding to `project-type`.
3. Populate individual files with essential content, such as `README.md`.

# Proposed Procedure
1. Write a script that will generate a directory and populate in it some files.
2. Modify the script to accept arguments.
3. Change script behavior based on arguments.
4. Modify README.md file.
5. **BONUS FEATURE: Design a way to add custom user-defined `project-type` schemes.

# Current Progress
- Basic requirements have been drawn out.