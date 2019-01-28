# GC

*Goodness Corp*? or *Garbage Collector*? Who knows... Maybe its *Gists Collection*, no its *Gone Cuties*!
LOL! ROFL! and LMAO...

I started this collection named "GC" in relationship but not only for JS.

You would feel as on a dump waste as well as happiest of happy-nanny nyan cat!

So, why **Javascript**?

I really not have an answer immediately...

Because, for example I can just run, in one line:

```
"foo".length
```

Or another one

```
"foo".match(/FOo/i)
```

Or even

```
++"foo1".match(/FOo(\d+)/i)[1]
```

Or *IIFE*, *JIT*, *events bubbling*, *functions binding*, whatever... you know?

Nevermind, if you do ;) Its kick your ASs! Just remeber - GC!

Ok, well, shuffling some another stuff...

# JS

* L = console.log() helper

    ```
    var L = (typeof console == 'object') ? console.log.bind(console) : function(){}
    ```
    or
    ```
    const L = console.log.bind(console)
    ```

* "Arraify" function arguments

    ```
    Array.prototype.slice.call(arguments)
    ```

* Backward-loop 

    ```
    var a = ['a','b','c']; for ( var i=a.length; i-- > 0; ) { L(a[i]) }
    ```

* Reading a -*py* config into js!

    ```
    var pycfg = require('fs').readFileSync('../config.py').toString()
    pycfg = pycfg.replace(/#.*\n|\r/g, '').replace('config = ', '').replace(/'/g, '"')
    L( pycfg.foo )
    ```

* Default function value

    ```
    function test(v) {
    var v = (typeof v == 'undefined') ? 'default' : v
    // v is 'default' or its own
    }
    ```

* Module 

```
var G = window || global || this;

(function ($a, L) {

    //private
    var self = this;
    var initData = {};
    var init = function(v) { Object.assign(self.initData, v) };
    var test = function() { L(self.initData) };

    //public
    ['init', 'test'].forEach(function (k) {
        $a[k] = self[k];
    });

    return $a;
})(
    G.$app || (G.$app = {}),
    G.L || (G.L = console.log.bind(console))
);

//run app
$app.init({foo:'Bar'});
```

# HTML/CSS

* Minimal pic

```
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR42mP8z8BQDwAEhQGAhKmMIQAAAABJRU5ErkJggg==">

<img src="data:image/gif;base64,R0lGODlhAQABAPABAP///wAAACH5BAEKAAAALAAAAAABAAEAAAICRAEAOw==">
```

```
background-image:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR42mP8z8BQDwAEhQGAhKmMIQAAAABJRU5ErkJggg==);

background-image:url(data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==);
```

# PHP

0_O Wooot!?

* one line terminal

    ```
    php -r "echo PHP_EOL;" > eol
    ```

internally have we equal to this?:

```
String.fromCharCode(13,10)
```

or just
```'\n'```

what about this ```\x0A \x0D``` , ```x13 x10``` ?

Blame it on the typewriters - better yet, that lever or button on the right side of them. The one used to start typing on the next line. When you activate it, it causes

    the carriage to 'return' to the right so the hammers are lined up on the left side of the paper (carriage return)
    the carriage to roll up so the hammers are lined up on the next 'line' down (line feed) 

In the early 1900's teletypwriters were used to relay messages. Teletypwriters were descendants of the telegraph, and used a code similar to ASCII, called Baudot (or Murray) code. An operator could type into the teletypewriter (tty for short) and print a message on another tty far away.

In this Baudot code, two special characters were designated for a Carriage Return(0x02) and a Line Feed(0x08). Baudot code went the way of the dinosaur for reasons outside the scope of this discussion, but the CR and LF characters were adopted by ASCII with different values:

    CR = 0x0D = \015 = \r
    LF = 0x0A = \012 = \n

historically

    Macintosh: \r
    Windows  : \r\n
    Unix     : \n

different operating systems interpret a logical newline

    Unix     : \n = \012
    Macintosh: \n = \015
    Windows  : \n = \012     if handled as ASCII
    Windows  : \n = \015\012 if handled as binary

But why ```x13 x10``` ?

```0x0D``` is hexadecimal ```0D``` which is decimal 13 which is octal 15 (or ```015```).
Similarly, ```0x0A``` is hexadecimal ```0A``` which is decimal 10 which is octal 12 (or ```012```).

Following php docs about strings interpolation:

Double quoted

If the string is enclosed in double-quotes ("), PHP will interpret more escape sequences for special characters:

\n - linefeed (LF or 0x0A (10) in ASCII)
\r - carriage return (CR or 0x0D (13) in ASCII)
\t - horizontal tab (HT or 0x09 (9) in ASCII)
\v - vertical tab (VT or 0x0B (11) in ASCII)
\e - escape (ESC or 0x1B (27) in ASCII)
\f - form feed (FF or 0x0C (12) in ASCII)
\\ - backslash
\$ - dollar sign
\" - double-quote
\[0-7]{1,3} - the sequence of characters matching the regular expression is a character in octal notation
\x[0-9A-Fa-f]{1,2} the sequence of characters matching the regular expression is a character in hexadecimal notation

As in single quoted strings, escaping any other character will result in the backslash being printed too. Before PHP 5.1.1, the backslash in ```\{$var}``` had not been printed.
The most important feature of double-quoted strings is the fact that variable names will be expanded. See [string parsing](https://php.net/manual/en/language.types.string.php#language.types.string.parsing) for details.

# SQL

    ```
    select from_unixtime(2147483647)
    ```

    => ```2038-01-19 05:14:07``` - 32-bit time_t limit (2038-year timestamp overflow)

# VI(M)

* Press **ESC** to switch mode

    **dd** - delete line

    **:w** - save, **:q** - quit

    **:wq** - write and quit

    **:q!** - quit without saving

* Cut and paste

    Position the cursor where you want to begin cutting.

    Press **v** to select characters (or uppercase **V** to select whole lines).

    Move the cursor to the end of what you want to cut.

    Press **d** to cut (or **y** to copy).

    Move to where you would like to paste.

    Press **P** to paste before the cursor, or **p** to paste after.

    Copy and paste is performed with the same steps except for step 4 where you would press **y** instead of **d**:

    **d** = delete = cut

    **y** = yank = copy

Deleted or copied text is placed in the unnamed register. If wanted, a register can be specified so the text is also copied to the named register. A register is a location in Vim's memory identified with a single letter. A double quote character is used to specify that the next letter typed is the name of a register.

For example, you could select the text ```hello``` then type ```"ay``` to copy "hello" to the ```a``` register. Then you could select the text ```world``` and type ```"by``` to copy "world" to the ```b``` register. After moving the cursor to another location, the text could be pasted: type ```"ap``` to paste "hello" or ```"bp``` to paste "world". These commands paste the text after the cursor. Alternatively, type ```"aP``` or ```"bP``` to paste before the cursor.

You remember? **"**, than **register**, than operation (**yY dD pP**)

And yes... Please don’t cut the purple trees!

Change the lineendings in the view:

```
:e ++ff=dos
:e ++ff=mac
:e ++ff=unix
```

This can also be used as saving operation (:w alone will not save using the lineendings you see on screen):

```
:w ++ff=dos
:w ++ff=mac
:w ++ff=unix
```

And you can use it from the command-line:

```
for file in $(ls *cpp)
do 
  vi +':w ++ff=unix' +':q' ${file}
done
```

# MISC

* Get first line of string

    js: ```s.split('\n')[0]```

    php: ```strtok($s, "\n")```

    py: ```s.split('\n', 1)[0]``` or another py: ```s.splitlines()[0]```

# SHELL

* Pack dir to TAR + GZ

    ```tar -zcvf name.tgz path```

* Pack 1 file (.gz added automatically)

    ```gzip path```

* Copy from your pc to host over ssh 

    ```scp source user@host:pathTo```

* Copy from host to your pc over ssh

    ```scp user@host:pathFrom pathTo```

* Download

    ```wget URL```

* Advanced download

    ```curl -fsSL URL -O``` (or replace ```-O``` to ```-o path```)

* Add user to root group

    ```usermod -aG sudo username```

* Install common dev stuff missing after clean install (like `vim` and `mc`)

    ```
    sudo apt-get update
    sudo apt-get upgrade
    sudo apt install net-tools apt-transport-https curl ca-certificates build-essential ubuntu-restricted-extras \
    software-properties-common python g++ make subversion git openssl libssl-dev openssh-client openssh-server \
    nullmailer mailutils screen vim mc
    ```

* `.scereenrc` (```sudo apt install screen```)

    ```
    vbell off
    altscreen on
    defutf8 on
    termcapinfo xterm ti@:te@
    hardstatus alwayslastline
    hardstatus string '%{= w}%-w[ %{= W}%n %t%{-} ]%+w%=[ %{= W}%H%{-} ] [ %{= W}%l%{-} ] [ %{= W}%d.%m.%Y %c:%s%{-} ]'
    ```

* `locale: Cannot set LC_*` errors

    ```
    locale: Cannot set LC_CTYPE to default locale: No such file or directory
    locale: Cannot set LC_ALL to default locale: No such file or directory
    ...
    ```

    - Client side fix:

        - Set appropriate env vars

        - Disable sending locale information over terminal
          (on OSX unset `Set locale environment variables on startup` in `Advanced` settings tab`)

    - Server side fix:

    ```
            apt-get purge locales
            apt install locales (locales-all)
            dpkg-reconfigure locales
            locale -a
    ```

# SSH

* Prevent `git@gitlab.com: Permission denied (publickey).` connection error

    ```
    eval "$(ssh-agent -s)"
    ssh-add -l
    ssh-add -K ~/.ssh/id_rsa (or other file)
    ```

or just `ssh add`

[How to add new ssh key](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/#adding-your-ssh-key-to-the-ssh-agent)

[About ssh agent](https://www.ssh.com/ssh/agent)

* Cannot connect to remote host with error:

    ```
    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
    @    WARNING: REMOTE HOST IDENTIFICATION HAS CHANGED!     @
    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
    IT IS POSSIBLE THAT SOMEONE IS DOING SOMETHING NASTY!
    Someone could be eavesdropping on you right now (man-in-the-middle attack)!
    It is also possible that a host key has just been changed.
    ```

    edit `.ssh/known_hosts` deleting old cached host fingerprint,
    than it will be recreated at next attemp

* Tunneling

    ```ssh -N -L localhost:6379:localhost:6379 example.com``` (-L ... -L ... to multiply number of ports)

# GIT

```
(git init)
git remote -v
(git remote add)
git branch
(git checkout -b new_branch)
(git checkout other_branch)
git status
git pull
(git merge)
git add .
git commit -m "msg"
git push -u origin master
```

# YARN

`npm -i -g yarn` or `brew install yarn` to install (Yarn)[https://yarnpkg.com/en/]

`yarn` - bring yarn into existing npm project

`yarn install foo` - install `foo` package

`yarn remove foo` - install `foo` package

`yarn dev` - run `dev` npm script

# OSX

* Shebang for `/usr/local/bin/*` shell scripts

    ```#!/bin/sh```

    Don't forget to set execute permissions - use `chmod +x /.../bin/foo` to set it

* Screenshots

    `CMD + SHIFT + 4`

# ESLINT

```
/* eslint-disable no-undef */
...
/* eslint-enable no-undef */
```
