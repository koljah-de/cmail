# cmail - CheckMail
A bash script that checks if an e-mail address is valid by connecting to the smtp server and checking the result.

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
