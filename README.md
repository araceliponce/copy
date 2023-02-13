
---
https://github.blog/2020-04-09-github-protips-tips-tricks-hacks-and-secrets-from-lee-reilly/

```diff
10 PRINT “BASIC IS COOL”
- 20 GOTO 11
+ 20 GOTO 10
```

`#C6E48B` `#7AC96F` `#249A3C` `#196127`
 
---


```
ng add angular-cli-ghpages
```
```
ng deploy --base-href "/nombre-del-repositorio/"
```

---

an app.module.ts

```
providers: [
  {
    provide: HTTP_INTERCEPTORS,
    useClass: UserinterceptorsService,
    multi: true
  }
],
```


---


crear karma.conf.js y en angular.json (en "test":{}, linea 78)

```
"karmaConfig": "karma.conf.js",

```

