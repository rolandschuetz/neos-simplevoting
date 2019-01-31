[![Latest Stable Version](https://poser.pugx.org/codeq/simplevoting/v/stable)](https://packagist.org/packages/codeq/simplevoting)
[![License](https://poser.pugx.org/codeq/simplevoting/license)](LICENSE)

# Simple voting

The package adds two content node types. `CodeQ.SimpleVoting:Survey` creates a survey, and `CodeQ.SimpleVoting:Survey.Option` are the voting options. 

Users can see the amount of votes and vote once per survey option.

These are ment to be used for user engagement - there is security against voting attacks. So when a user votes a cookie is set on their browser, allowing users to vote up to one time for each survey option. 

## Installation

CodeQ.SimpleVoting is available via packagist. `"codeq/simplevoting" : "~1.0"` to the require section of the composer.json
or run:

```bash
composer require codeq/simplevoting
```

We use semantic-versioning so every breaking change will increase the major-version number.

## License

Licensed under MIT, see [LICENSE](LICENSE)

## Contribution

We will gladly accept contributions. Please send us pull requests.
