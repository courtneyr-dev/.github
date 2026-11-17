# Contributing

Thanks for helping. Bug reports, feature ideas, documentation fixes, testing, and code are all welcome.

If the repository has its own README or `docs/` folder, check it first. It explains how to set up that project and run its tests.

## Report a bug

Open an issue with the **Bug report** form. Include your WordPress and PHP versions, the plugin or theme version, and the steps that show the problem. If you can, test with only this plugin active and a default theme first, so you can rule out conflicts.

For a security problem, don't open an issue. Follow [SECURITY.md](SECURITY.md) instead.

## Suggest a feature

Open an issue with the **Feature request** form. Start with the problem you want to solve, not the solution. That helps me find the smallest change that fixes it.

## Send a pull request

1. Fork the repository and create a branch from `main`, for example `fix/empty-title` or `feature/export-csv`.
2. Keep each pull request to one change. Two small pull requests get reviewed faster than one large one.
3. Follow the coding standards the repository uses. Most of my WordPress projects use the [WordPress Coding Standards](https://developer.wordpress.org/coding-standards/), with `phpcs` and the linters set up in the repository.
4. Run the repository's tests and linters before you push. CI runs them again on your pull request.
5. Fill in the pull request template, and link the issue it closes (`Closes #123`).

### Commit messages

Commits use [Emoji-Log](https://github.com/ahmadawais/Emoji-Log): one emoji, a label, and an imperative sentence.

```text
🐛 FIX: Keep the title when the post has no content
📦 NEW: Add a CSV export
👌 IMPROVE: Load the editor script only on posts
📖 DOC: Explain the export setting
```

Don't worry if you get this wrong. I can adjust it when I merge.

### AI-assisted contributions

You can use AI tools. Say so in the pull request, and make sure you've read, run, and understood every line you submit.

## Review

I review pull requests as time allows. I may ask for changes or suggest a different approach.

## Code of conduct

Everyone who takes part follows the [Code of Conduct](CODE_OF_CONDUCT.md).
