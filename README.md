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

