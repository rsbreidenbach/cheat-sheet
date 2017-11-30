# Cheat Sheet

Things I know I should know but forget

## OpenSSL

Check a private key

    openssl rsa -in privateKey.key -check

Check a certificate

    openssl x509 -in certificate.crt -text -noout

## ls

Sort by file size

    ls -lS
