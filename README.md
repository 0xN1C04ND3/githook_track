### GitHook
Simple track tool using git hooks

## Usage
Executing `track` with start or stop as argument will start or stop tracking the time spent on the project.
Making a commit will automatically push the commmit to the remote repository.
Log file is stored in the root directory of the project as `track.log`.

To commit without pushing, use `git commit --no-verify`.

## Installation
- Put the `pre-commit` and `post-commit` files in `.git/hooks` directory of your project
- Make sure the files have execution permission with `chmod +x pre-commit post-commit`
- Put `track.sh` in the root of your project
- Make sure the file has execution permission with `chmod +x track.sh`
- Done!
