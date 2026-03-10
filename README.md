# veit1337

![Maintained](https://img.shields.io/badge/Maintained%3F-yes-green.svg)

Hi everyone :)

This repository contains some settings and configs that I find useful for
developing software.

Furthermore, you can find some of my social media links.

## Social media

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/veit-gemmer/)
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?logo=youtube&logoColor=white)](https://www.youtube.com/@veit1337)
[![SoundCloud](https://img.shields.io/badge/SoundCloud-%23FF5500.svg?logo=soundcloud&logoColor=white)](https://soundcloud.com/ve1t)


## Settings and configs

### Git

In the `.gitconfig`, you can find some handy settings that make the experience
using [git](https://git-scm.com/) in the shell more convenient.

I encourage every developer to use a `commit_template.txt`.
Instead of just specifying a commit message with

```bash
git commit -m "some undescriptive comment"
```

you just run

```bash
git commit
```

which takes you to your template where you can easily write a proper multi-line
commit message (if necessary).

It also allows you to remind yourself of any present commit-message-guidelines
you and your team follow.

### Pre-commit hooks

[Pre-commit](https://pre-commit.com/) hooks are a great way to contribute to
high code quality.
You can find some basic set of hooks in the `.pre-commit-config.yaml` that can
be used across multiple projects in all kinds of languages.

I have to admit that I used

```bash
git commit --no-verify
```

a lot of times to ignore the hooks. It is a great flag.

### VSCode

[VSCode](https://code.visualstudio.com/) is my favorite IDE. Even though the UI
is a bit overloaded in my opinion, it has some nice clickibunti tools, it is
highly configurable, it has a rich plug-in ecosystem, and you can still have
[Vim](https://www.vim.org/) keybindings.

[Github Copilot](https://github.com/features/copilot) is also a powerful tool
that is also well integrated.

I listed the `settings.json`, `keybindings.json`, and `extensions.json` that I
enjoy.

### README

Every repository should have a proper maintained `README.md`. For new users or
developers, there is nothing more frustrating than an outdated README.

I like the `README_template.md` since it is complete and you sometimes forget
an important section.

### Acknowledgments

[How Core Git Developers Configure Git by Scott Chacon](https://blog.gitbutler.com/how-git-core-devs-configure-git)

[My favorite Git commit by David H.W. Thompson](https://dhwthompson.com/2019/my-favourite-git-commit)

[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
