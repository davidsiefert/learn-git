## Set a global .gitignore

```bash
git config --global core.excludesfile ~/.gitignore
```

### Ignore files for emacs

```
*~
\#*\#
```

## Ignore files for ensime

```
.ensime
.ensime_cache
```

## Ignore files for eclipse

```
.settings
.classpath
.cache-main
.cache-tests
.project
```

## Setting username/email

Globally

```
git config --global user.name "My Name"
git config --global user.email "myname@email.com"
```

Drop the ```--global``` for a per-repo configuration.
