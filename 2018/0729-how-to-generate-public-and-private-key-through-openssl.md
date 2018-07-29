Fast command
===

Generate a 2048 bit RSA Key

```
openssl genrsa -des3 -out private.pem 2048
```

Export the RSA Public Key to a File

```
openssl rsa -in private.pem -outform PEM -pubout -out public.pem
```

As a ref to:
https://rietta.com/blog/2012/01/27/openssl-generating-rsa-key-from-command/
