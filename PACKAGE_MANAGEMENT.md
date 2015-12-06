# To update tlmgr metadata (once every week)

```
$ tlmgr update --self
```

# To search for a package 

```
$ tlmgr search SEARCH_STRING [--all|--file]
```

```
     --all  — Search everything: package names, descriptions and filenames
     --file - List all filenames containing SEARCH_STRING
```

# To install a new package

```
$ tlmgr install PACKAGE_NAME [--reinstall]
```

# To list installed packages

```
$ tlmgr list --only-installed
```

# To list packages that have a newer version available

```
$ tlmgr update --list
```

# To update a package

```
$ tlmgr update PACKAGE_NAME
```

# To update all package

```
$ tlmgr update --all
```

# To remove a package

```
$ tlmgr remove PACKAGE_NAME
```
