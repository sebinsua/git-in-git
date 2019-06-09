# `git-in-git`

Have you ever wondered what [git](https://git-scm.com) does under the hood?

1. Initialise the repository with `.git` as `src`.
2. Create a `README.md`, add it to staging, and create a commit with this change inside.
3. Add the remote to `.git/config`, and create a commit with this change inside.
4. Create a new branch `change-to-readme` to update the `README.md` with items 3 and 4, and create a commit with this change inside.
5. [Demonstrate these incremental changes to Git using a pull request](https://github.com/sebinsua/git-in-git/pull/1).

