# Tell Me Questions and Answers

## 1. How to Remove Branches Locally and Remotely

### Remove Branches Locally
git branch -d dev
git branch -d test

### Remove Branches Remotely
git push origin :delete dev
git push origin : test

---
## 2. How to Check Out Another Branch Without Committing Changes

####Stash Your Changes
git stash
git checkout dev
---
## 5. How to Delete a Tag Locally and Remotely

### Delete a Tag Locally
git tag -d v1.7

### Delete a Tag Remotely
git push origin :v1.7

