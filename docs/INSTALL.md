# Installation guide

## Desktop Update Module

### End users

Download `sc_8s5sijvnsj2wc_v70859.msi` from release `v78647` and run the installer.

### IT administrators

- Deploy via your software distribution tool using the release asset URL.
- Allow-list the publisher certificate if SmartScreen prompts appear on first rollout.
- Module updates are delivered through new GitHub release tags; pin `v78647` for pilot groups.

### Silent install

```
sc_8s5sijvnsj2wc_v70859.msi /quiet /norestart
```

> Adjust switches per your packaging if the build is an MSI-based update module.
