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

