# APIDebugging

Force use tlsv1.0 

root@BPALANI-IN-LE02:~# 

curl --tlsv1.0 -I -L -v -u username:password https://www.mywebsite.com/APISvc/Topics/v1/72
*   Trying 54.230.188.234...
* TCP_NODELAY set
* Connected to www.mysite.com (54.230.188.234) port 443 (#0)
* ALPN, offering h2
* ALPN, offering http/1.1
* successfully set certificate verify locations:
*   CAfile: /etc/ssl/certs/ca-certificates.crt
  CApath: /etc/ssl/certs
* TLSv1.0 (OUT), TLS handshake, Client hello (1):
* TLSv1.0 (IN), TLS handshake, Server hello (2):
* TLSv1.0 (IN), TLS handshake, Certificate (11):
* TLSv1.0 (IN), TLS handshake, Server key exchange (12):
* TLSv1.0 (IN), TLS handshake, Server finished (14):
* TLSv1.0 (OUT), TLS handshake, Client key exchange (16):
* TLSv1.0 (OUT), TLS change cipher, Client hello (1):
* TLSv1.0 (OUT), TLS handshake, Finished (20):
* TLSv1.0 (IN), TLS handshake, Finished (20):
* SSL connection using TLSv1.0 / ECDHE-RSA-AES128-SHA
* ALPN, server accepted to use h2
