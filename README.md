# Semantic Commit (scommit)

Semantic Commit (scommit) is a Python script that uses the ChatGPT API to auto-generate commit messages for your git commits. You can use it exactly like `git commit`:

`scommit -a`

is equivalent to:

`git commit -a -m "auto-generated commit message"`

Think of `scommit` as an alias for `git commit` that appends `-m "message"` with an auto-generated message. That's it! I recommend using this when you don't actually care about commit messages, but want them to be slightly more informative than "sdflskdjafks". Plus, it uses more GPU's than regular commits, and we all know GPU usage is a proxy for agency.

## Installation
`pip install scommit`

You should get command-line tool called `scommit` that you can use just like git commmit.

You also need to set your [OpenAI API key](https://platform.openai.com/account/api-keys) as an environment variable named OPENAI_API_KEY for scommit to work. Add this line in your `.bashrc` or `.zshrc`:

`export OPENAI_API_KEY=your-api-key`

## License

This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file for details.