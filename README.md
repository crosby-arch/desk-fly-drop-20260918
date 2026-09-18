TEMPORARY public drop. Delete after download.

File: crosby-dashboard-8e6fc4d.tar.gz
sha256: 2cb8ac492dc2554e0629186629c802c645720f5dddbe6af65df8e3b4e7e32c66
bytes: 5079652

Reconstruct:

```
curl -fsSL https://raw.githubusercontent.com/crosby-arch/desk-fly-drop-20260918/main/chunk00.txt \
  https://raw.githubusercontent.com/crosby-arch/desk-fly-drop-20260918/main/chunk01.txt \
  https://raw.githubusercontent.com/crosby-arch/desk-fly-drop-20260918/main/chunk02.txt \
  https://raw.githubusercontent.com/crosby-arch/desk-fly-drop-20260918/main/chunk03.txt \
  https://raw.githubusercontent.com/crosby-arch/desk-fly-drop-20260918/main/chunk04.txt \
  https://raw.githubusercontent.com/crosby-arch/desk-fly-drop-20260918/main/chunk05.txt \
  https://raw.githubusercontent.com/crosby-arch/desk-fly-drop-20260918/main/chunk06.txt \
  https://raw.githubusercontent.com/crosby-arch/desk-fly-drop-20260918/main/chunk07.txt \
  | tr -d '\n' | base64 -d > crosby-dashboard-8e6fc4d.tar.gz
sha256sum crosby-dashboard-8e6fc4d.tar.gz
```
