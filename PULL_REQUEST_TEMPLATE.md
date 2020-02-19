Thank you for the interest in contributing. To review and possibly merge as soon as possible, please make sure the following is in order:

- [ ] Use a very clear title
- [ ] Prefix the PR title with the Taiga bug number (`[ABC-123] My clear title`)
- [ ] When making a change with a corresponding [Taiga bug](https://taiga.getbyterub.org/project/michael-rfc-hwallet-1-implementation/issues/), include the bug number in the PR description
- [ ] When making a change with no Taiga bug yet, create a [new entry](https://taiga.getbyterub.org/project/michael-rfc-hwallet-1-implementation/issues/) and include the bug number in the PR description

The repository maintainer will likely merge the request in the following way:

```
$ git checkout -b pr-name
$ git pull git://github.com/<contributor>/<thisrepo>.git <branch>
$ git checkout master
$ git merge --no-ff pr-name
$ git branch -d pr-name
$ git push
```

For questions or problems, ask us on irc://chat.freenode.net/byterub-hardware/.
