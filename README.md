# get-github-pr-review-comments

Get PR review comments.

## Install

Install with [npm](https://www.npmjs.com/):

    npm install get-github-pr-review-comments

## Usage

    Usage
      $ get-github-pr-review-comments --repo owner/repo --projectRoot /path/to/project --token <GitHubToken> <sha>

    Options
      --repo  owner/repo
        e.g.) azu/get-github-pr-review-comments
      --projectRoot -p /path/to/root-project
        e.g.) /Users/azu/get-github-pr-review-comments
      --token GitHub Token
        Get from https://github.com/settings/tokens/new
        or
        export GH_TOKEN=XXX
        
     Example:
        get-github-pr-review-comments --repo azu/get-github-pr-review-comments --projectRoot /path/to/get-github-pr-review-comments --token xxx \`git rev-parse HEAD\`
    


## Changelog

See [Releases page](https://github.com/azu/get-github-pr-review-comments/releases).

## Running tests

Install devDependencies and Run `npm test`:

    npm i -d && npm test

## Contributing

Pull requests and stars are always welcome.

For bugs and feature requests, [please create an issue](https://github.com/azu/get-github-pr-review-comments/issues).

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Author

- [github/azu](https://github.com/azu)
- [twitter/azu_re](https://twitter.com/azu_re)

## License

MIT © azu
