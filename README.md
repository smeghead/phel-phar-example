# phel-phar-example

## Setup

```bash
$ curl -OL https://github.com/phel-lang/phel-lang/releases/download/v0.18.0/phel.phar
$ chmod +x phel.phar
```

### Check environment

```bash
$ ./phel.phar doctor
Checking requirements:
 - PHP >= 8.2: OK
 - json extension: OK
 - mbstring extension: OK
 - readline extension: OK
Your system meets all requirements.
```

### Run script

```bash
$ ./phel.phar run src/hello.phel 
Hello, phel
             THE PHEL LANGUAGE
```

```bash
$ ./phel.phar run src/call.phel  
call file
from module.
```

