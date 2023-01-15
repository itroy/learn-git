
# Cheatsheet

This is a reference list of the most commonly used Git commands. (You might consider bookmarking this handy page.) Try to familiarize yourself with the commands so that you can eventually remember them all:

## Commands related to a remote repository:
    git clone git@github.com:USER-NAME/REPOSITORY-NAME.git
    git push or git push origin main (Both accomplish the same goal in this context)
## Commands related to the workflow:
    git add .
    git commit -m "A message describing what you have done to make this snapshot different"
## Commands related to checking status or log history
    git status
    git log

## The basic Git syntax is program | action | destination.

For example,

    git add . is read as git | add | ., where the period represents everything in the current directory;
    git commit -m "message" is read as git | commit -m | "message"; and
    git status is read as git | status | (no destination).

## Git Best Practices

    - Atomic commits - make commits related to one feature or task of your program.
    - Leverage atomic commits to make your commit messages useful to future collaborators.

## Good Commit Messages

    1. Separate subject from body with a blank line
    2. Limit the subject line to 50 characters
    3. Capitalize the subject line
    4. Do not end the subject line with a period
    5. Use the imperative mood in the subject line
    6. Wrap the body at 72 characters
    7. Use the body to explain what and why vs. how