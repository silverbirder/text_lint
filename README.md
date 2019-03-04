## text_lint

## how to

```
$ npm install
$ echo "I love docker" >> sample.md
$ npm run lint sample.md -s
text_lint/sample.md
  1:8  ✓ error  docker => Docker  prh

✖ 1 problem (1 error, 0 warnings)
✓ 1 fixable problem.
Try to run: $ textlint --fix [file]
```
