# Jade-Nathan-Noella-Aurelien-Git-GithubESGI2

## Understanding `git log` in Git

The `git log` command is used to display the commit history of a Git repository. It shows a list of commits along with their details like the hash, author, date, and commit message.

## Basic Usage

To view the commit history, simply type:

This command will show a list of all commits starting with the most recent. By default, it displays the commit hash, author, date, and the commit message.

## Viewing Specific Details

You can customize the output of `git log` with various options:

- To see a condensed, one-line version of the history:

- To include which files were altered and the relative number of changes in each file:

- To view the complete diff of each commit:

## Filtering the Log

You can also filter the output based on time, author, or files:

- To show commits by a specific author:

- To show commits before a specific date:

- To show commits that include a particular file:

## Visualizing Commit History

For a graphical representation of the commit history:

- Use the `--graph` option to see an ASCII graph of the branch and merge history:

Combining `--graph` with `--oneline` and `--all` gives a clear overview of the entire history, including all branches:

`git log` is a powerful tool to understand the evolution of a project. With its various options and filters, you can get detailed insights into the history of your repository.
