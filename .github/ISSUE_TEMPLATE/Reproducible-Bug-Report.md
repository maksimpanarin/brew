---
name: Reproducible Bug Report
about: Submit an issue so we can investigate

---

**Please note we will close your issue without comment if you delete, do not read or do not fill out the issue checklist below and provide ALL the requested information. If you repeatedly fail to use the issue template, we will block you from ever submitting issues to Homebrew again.**

- [ ] are reporting a bug others will be able to reproduce and not asking a question. If you're not sure or want to ask a question do so on our Discourse: https://discourse.brew.sh
- [ ] ran a `brew` command and reproduced the problem with multiple formulae? If it's a problem with a single, official formula (not cask) please file this issue at Linuxbrew/homebrew-core: https://github.com/Linuxbrew/homebrew-core/issues/new. If it's a `brew cask` problem please file this issue at https://github.com/caskroom/homebrew-cask/issues/new. If it's a tap (e.g. Homebrew/homebrew-php) problem please file this issue at the tap.
- [ ] ran `brew update` and can still reproduce the problem?
- [ ] ran `brew doctor`, fixed all issues and can still reproduce the problem?
- [ ] ran `brew config` and `brew doctor` and included their output with your issue?

To help us debug your issue please explain:
- What you were trying to do (and why)
- What happened (include command output)
- What you expected to happen
- Step-by-step reproduction instructions (by running `brew` commands)
