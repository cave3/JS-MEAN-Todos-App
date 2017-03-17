# JS-MEAN-Todos-App

Simple todos app that runs on the MEAN stack

---

## MEAN stack app initialized with:
```
$ npm init

$ npm install express mongojs ejs body-parser --save
```

----
Set user/pw in routes/todos.js

```
var db = mongojs('mongodb://<USER>:<PASS>@ds133290.mlab.com:33290/cave3_meantodos', ['todos']);
```