# Copy-Passed
#### A remote clipboard application

---
[site](https://copy-passed.web.app)
---

## Features 
- [x] bash console access
- [ ] ~~windows batch console access~~
- [ ] windows powershell console access
- [x] multiple registered computers/consoles

---

## linked projects
[Android app](https://github.com/ocular-data/copy-passed-android)

[Firebase hosting website](https://github.com/ocular-data/copy-passed-terminalAccess)

[GO clipboard](https://github.com/ocular-data/copy-passed-go)

---

### explanations
This app allows uses to copy paste text cross
platforms as long as they have internet.

console access can be done by piping in or 
out of the program.

```bash
$ echo 12 | ./copy_passed.sh
{"success":true}
$ ./copy_passed.sh
12
```