#Serverless2 Deployment !

https://zeit.co/login


```
npm i -g now
now test.html
enter your email
submit email
now test.html   (again..)
for github integration check docs https://zeit.co
you need there just a file now.json, without "builder" section!
```


```
{
  "name": "mein Serverless 2 Deployment!",
  "version": 2,
  "builder": [
    {
      "src": "*.html",
      "use": "@now/static"
    },
    {
      "src": "*.js",
      "use": "@now/node"
    },
    {
      "src": "*.php",
      "use": "@now/php"
    }
  ]
}
```
