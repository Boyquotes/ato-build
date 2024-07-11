Demo
https://boyquotes.github.io/ato-build/

```
bun run build && sed -i '' "s#/static#/ato-build/static#g" build/index.html && rm -rf ../ato-build/* && cp -r build/* ../ato-build && cd ../ato-build && git add . && git commit -m"new deploy" && git push && cd -
```
