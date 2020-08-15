# How to contribute

Thank you for your interest in contributing to natlas projects. If you haven't already, please consider joining [our discord](https://discord.gg/VMbyMMT), where you'll be able to chat with other users in the community as well as other developers who are interested in contributing.

## Testing

We currently don't have any real testing in place. If testing is something you're passionate about or are interested in helping out with, please chat with the @natlas/core team.

## Documentation

Natlas documentation is powered by GitHub Pages. All documentation is written using Hugo with the Docsy theme. If you'd like to contribute documentation, please fork the [docs.natlas.io](https://github.com/natlas/docs.natlas.io) project and submit a Pull Request with your changes.

## Code

Code contributions will be automatically analyzed by codeclimate and LGTM, which have been configured to enforce our style guides. For python, that means that we mostly follow PEP8 with a few exceptions - those being the exceptions required by the [black](https://github.com/psf/black) code formatter. This is a decision made for code accessibility and allows each developer to display the code with the level of indentation that they want without having to use any complicated re-indention processes.

As is the requirement with all projects hosted on Github, all contributions to natlas projects will be automatically licensed under whatever the license of the project is. The preferred license for natlas projects at this time is [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/).

Please use a brief, but clear, log message for your commits. One line messages are fine for small changes, but larger changes should have a more detailed explanation provided in the extended description. The extended description is separated from the short description via a blank line, like so:

```
$ git commit -m "My short description...
>
> My much longer description that talks about my changes in greater detail."
```

## Security Testing

The natlas developers care deeply about security, many of us coming from a security background. To this end, we encourage you to look for vulnerabilities and perform tests on the natlas projects. At this time, please only perform tests against locally installed versions of the projects. See our [security policy](SECURITY.md) for more information.
