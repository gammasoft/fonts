fonts
=====

```bash
____ ____ ____ _       _    ____ ____ _  _ _ _  _ ____    ____ ____ _  _ ___ ____ 
|    |  | |  | |       |    |  | |  | |_/  | |\ | | __    |___ |  | |\ |  |  [__  
|___ |__| |__| |___    |___ |__| |__| | \_ | | \| |__]    |    |__| | \|  |  ___] 
____ ____ ____    ___ _  _ ____    ____ ____ _  _ ____ ____ _    ____   / 
|___ |  | |__/     |  |__| |___    |    |  | |\ | [__  |  | |    |___  /  
|    |__| |  \     |  |  | |___    |___ |__| | \| ___] |__| |___ |___ . 
```

**Instalation**
    npm install fonts
    
**Usage**
```JavaScript
var fonts = require("fonts");
fonts("Cool looking fonts").print();
fonts("for the console!").print();
fonts("--------------").print();
fonts("abcdefghijklmnoprqstuvxywz").print();
fonts("!?").print();
fonts("0123456789").print();
fonts("+ - _ , . : ;").print();
```

**Using your custom font**
```JavaScript
var fonts = require("fonts");
var myCoolCustomFont = require("myCoolCustomFont");
fonts("Cool looking fonts", myCoolCustomFont).print();
```
