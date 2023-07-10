```bash
openssl genrsa -des3 -passout pass:---- -out server.pass.key 2048
openssl rsa -passin pass:---- -in server.pass.key -out server.key
openssl req -new -key server.key -out server.csr
openssl x509 -req -sha256 -days 365 -in server.csr -signkey server.key -out server.crt
```

*Replace the password ---- with the desired value*
