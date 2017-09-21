# Contributing

We'd love for you to contribute to our repository, yet we have a certain set of rules that come within helping programming with us. Here are a bunch of guidelines that'd we like for you to follow.

 - [Code Rules](#cr)
 - [Issues](#is)
 - [Git Rules](#gr)

*Note that these rules are a fork of AngularJS's.*

## <a name="cr"></a> Coding Rules

To ensure consistency throughout the source code, keep these rules in mind as you are working:

- All features or bug fixes must be tested by one or more specs.
- With the exceptions listed below, we follow the rules contained in Google's JavaScript Style Guide:
    - Do not use namespaces: Instead, wrap the entire AngularJS code base in an anonymous closure and export our API explicitly rather than implicitly.
    - Wrap all code at 100 characters.

## <a name="is"></a> Issues

Got any issues you can checkout the repo issues page [here](../../../issues)!

Note that before you submit an issue you should search the archive, make sure you havent asked a question that was already answered.

- **Bug** Duh, its a bug.
- **Enhancement** Improve the repository.
- **Duplicate** Already submitted.
- **Help Wanted** Unaware how to continue.
- **Invalid** Invalid content.
- **Question** Duh.
- **WontFix** Things that wont be fixed.

## <a name="gr"></a> Git Commit Guidelines

### Format

#### Message Format

All messages must following set of rules, whereas a footer or body may not be required for the given situation!

```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

The header and scope are mandatory.

#### Revert

A revertion of previous content must be in the format of..

```
revert(<scope>): <subject>
```

#### Type

- feat: A new feature
- fix: A bug fix
- docs: Documentation only changes
- style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- refactor: A code change that neither fixes a bug nor adds a feature
- perf: A code change that improves performance
- test: Adding missing or correcting existing tests
- chore: Changes to the build process or auxiliary tools and libraries such as documentation generation

#### Scope

The location in which the content was changed.
 
#### Subject

- use the imperative, present tense: "change" not "changed" nor "changes"
- don't capitalize first letter
- no dot (.) at the end

#### Body

Just as in the subject, use the imperative, present tense: "change" not "changed" nor "changes". The body should include the motivation for the change and contrast this with previous behavior.

This content is optional.

#### Footer

The footer should contain any information about Breaking Changes and is also the place to reference GitHub issues that this commit closes.

Breaking Changes should start with the word BREAKING CHANGE: with a space or two newlines. The rest of the commit message is then used for this.