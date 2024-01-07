# How to Contribute #
We're always looking for people to help make Kavita even better, there are a number of ways to contribute.

## Development ##

### Tools required ###
- HTML/Javascript editor of choice (VS Code/Sublime Text/Webstorm/Atom/etc)
- [Git](https://git-scm.com/downloads)
- If using an OS other than Windows, please install [Hugo](https://github.com/gohugoio/hugo/releases/latest)

### Getting started ###

1. Fork this repo
2. Clone the repository into your development machine. [*info*](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github)
3. Open Git Bash
4. Navigate to the repo
    - `cd [your dir structure]/kareadita.github.io`
5. Run Hugo
    - `./hugo.exe server`
    - Or 
6. Open http://localhost:1313/


### Contributing Code ###
- If you're adding a new, already requested feature, please comment on [Github Issues](https://github.com/Kareadita/Kavita/issues "Github Issues") so work is not duplicated (If you want to add something not already on there, please talk to us first).
- Make meaningful commits, or squash them.
- Feel free to make a pull request before work is complete, this will let us see where its at and make comments/suggest improvements.
- Reach out to us on the discord if you have any questions.
- Commit with *nix line endings for consistency (We checkout Windows and commit *nix).
- One feature/bug fix per pull request to keep things clean and easy to understand.
- Use 4 spaces instead of tabs.

### Pull Requesting ###
- Only make pull requests to main.
- You're probably going to get some comments or questions from us, they will be to ensure consistency and maintainability.
- We'll try to respond to pull requests as soon as possible, if its been a day or two, please reach out to us, we may have missed it.
- Each PR should come from its own [feature branch](http://martinfowler.com/bliki/FeatureBranch.html) not develop in your fork, it should have a meaningful branch name (what is being added/fixed)
    - new-feature (Bad)
    - fix-bug (Bad)
    - patch (Bad)
    - develop (Bad)
    - feature/new-hero-layout (Great)
    - bugfix/dockerhub-link-fix (Great)

If you have any questions about any of this, please let us know.
