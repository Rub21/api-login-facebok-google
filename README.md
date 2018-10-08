# API for login in facebook and google in secure mode

-  Generate the certificates

```
openssl req -x509 -newkey rsa:2048 -keyout keytmp.pem -out cert.pem -days 365
openssl rsa -in keytmp.pem -out key.pem
```

It will create 3 files:

```
key.pem
cert.pem
keytmp.pem
```

- Star running the App:

```
npm start
```