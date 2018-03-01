# cmail - CheckMail
A bash script that checks if an email address is valid or not.

### Preparing
You need to install:
 * dig
 * nc (netcat)
 * expact
 * telnet

### Usage: 
```bash
cmail [-d <email.domain>] [-e <smtp-server>] [-p <port>] mail@address
      -d: specifies the email domain
      -e: specifies the smtp server domain (mail exchanger)
      -p: specifies the smtp server port
      -v: verbose. Prints detailed information
```
