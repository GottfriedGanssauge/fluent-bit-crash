# Demonstrate failure case for fluent-bit issue #9677

See [github issue](https://github.com/fluent/fluent-bit/issues/9677)

To run the demonstration just run

~~~shell
$ docker compose up
~~~

## Description

For using the https access to azurite a self-signed certificate has been added with [mkcert](https://github.com/FiloSottile/mkcert)
The certificate is in file [azurestorage.local.pem](./azurestorage.local.pem) and the key for it is in [azurestorage.local-key.pem](./azurestorage.local-key.pem).
