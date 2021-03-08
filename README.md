EMIF Adapter Schema
====================

Schemas used for communication between Elvia and external [Elhub](https://dok.elhub.no/mdok/elhub-messaging-interface-emif) adapter.

## Tag creation
Tagging in github means you have to add the following tag and release name like `v<versionnumber>` i.e. `v0.1.0`. Azure DevOps will remove the 'v' and build and pack the version release when its available.

##### Version basics
A specific version number is in the form Major.Minor.Patch[-Suffix], where the components have the following meanings:

Major: Breaking changes
Minor: New features, but backwards compatible
Patch: Backwards compatible bug fixes only
-Suffix (optional): denotes a pre-release version.
Examples:
```
1.0.1
6.11.1231
4.3.1-rc
2.2.44-beta1
```

##### Pre-release versions

Package developers generally follow recognized naming conventions:

-alpha: Alpha release, work-in-progress and experimentation.
-beta: Beta release, feature complete for the next planned release, but may contain known bugs.
-rc: Release candidate, final (stable) unless significant bugs emerge.
 Note

```
1.0.1
1.0.1-zzz
1.0.1-rc
1.0.1-open
1.0.1-beta
1.0.1-alpha2
1.0.1-alpha
1.0.1-aaa
```
