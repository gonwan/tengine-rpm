## Tengine RPM

- Unofficial Tengine RPM packaging for quick installation. Copied and modified from offical [EPEL](https://docs.fedoraproject.org/en-US/epel/) package. Find diffs with:
```shell
# diff -ru nginx.spec tengine.spec
```
- Separate package names are used. But they are in-place substitution for orginal nginx* packages, for easier operation.
- Copy all file to `~/rpmbuild/SOURCES`, and build:
```shell
# rpmbuild -ba tengine.spec
```

  
