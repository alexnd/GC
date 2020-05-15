# GC

*Goodness Corp*? or *Garbage Collector*? Who knows...

Maybe its *Gists Collection*, no its *Gone Cuties*! LOL! ROFL! and LMAO...

I started this collection named "GC" in relationship but not only for JS.

You would feel as on a dump waste as well as happiest of happy-nanny nyan cat!

To be clear, this is not just a garbage-like log, but mix of proven solutions even with copy-paste from good sites.

Enjoy!

So, why **Javascript**?

I really not have an answer immediately...

Because, for example I can just run, in one line:

`"foo".length`

Or another one

`"foo".match(/FOo/i)`

Or even

`++"foo1".match(/FOo(\d+)/i)[1]`

Or *IIFE*, *JIT*, *events bubbling*, *functions binding*, whatever... you know?

Nevermind, if you do ;) Its kick your ASs! Just remember - GC!

Ok, well, shuffling some another stuff...

# [MARKDOWN](https://github.com/showdownjs/showdown/wiki/Showdown's-Markdown-syntax)

# JS

* L = console.log() helper

    `var L = (typeof console == 'object') ? console.log.bind(console) : function(){}`

or

    `const L = console.log.bind(console)`

* "Arraify" function arguments

    `Array.prototype.slice.call(arguments)`

* Backward-loop 

    `var a = ['a','b','c']; for ( var i=a.length; i-- > 0; ) { L(a[i]) }`

* Random array element

    `a[Math.floor(Math.random() * a.length)]`

* Reading a -*py* config into js!

    ```
    var pycfg = require('fs').readFileSync('../config.py').toString()
    pycfg = pycfg.replace(/#.*\n|\r/g, '').replace('config = ', '').replace(/'/g, '"')
    L( pycfg.foo )
    ```

* Default function argument value

    ```
    function test(v) {
    var v = (typeof v == 'undefined') ? 'Foo' : v
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

# [VUE](https://ru.vuejs.org/v2/guide/index.html)

component.vue

```
<template>
  <foo-bar v-model="x" @click.prevent="barFoo">
</template>
<script>
/* eslint-disable vue/no-unused-components */
import { mapState } from 'vuex'
import FooBar from 'theme/components/Foo'
export default {
  name: 'Bar',
  components: {
    FooBar
  },
  props: {
    msg: {
      type: String,
      required: false,
      default: ''
    }
  },
  data () {
    return {
      x: 0
    }
  },
  created () {},
  beforeMount () {},
  computed: {
    ...mapState({
      currentUser: state => state.user.current,
      barX () {
        return 1000 * this.x
      }
    })
  },
  methods: {
    barFoo() {}
  }
}
</script>
```

Init VUE PWA boilerplate

```
sudo npm i -g @vue/cli @vue/cli-init @vue/cli-plugin-pwa`
vue init pwa#development projectname
cd projectname
npm i
npm run dev
```

# SHELL

* Pack dir to TAR + GZ

    `tar -zcvf name.tgz path`

* Unpack TGZ

    `tar -xzf name.tgz`

* Pack dir to BZ2 without absolute path`

    `tar -c -j -f site1.tbz -C /var/www site1`

* Pack 1 file (.gz added automatically)

    `gzip path`

* Copy from your pc to host over ssh 

    `scp source user@host:pathTo`

* Copy from host to your pc over ssh

    `scp user@host:pathFrom pathTo`

* Download

    `wget URL`

* Advanced download

    `curl -fsSL URL -O` (or replace `-O` to `-o path`)

* Add user to root group

    `usermod -aG sudo username`

* Recursively set owner:group

    `chown -R username:group /path/*`

* Recursively fix R/W permissions

    `cd somewhere && find . -type d -exec chmod 777 {} \; && find . -type f -exec chmod 666 {} \;`

    or

    ```chmod 755 $(find /path/to/base/dir -type d)
    chmod 644 $(find /path/to/base/dir -type f)```

* Show Debian/Ubuntu linux version

    `lsb_release -a`

* List media drives

    `fdisk -l`
   
* List usb devices

    `lsusb`

* Backup disk to file, than restore it

    ```
    dd if=/dev/hda1 of=./part1.image - to backup
    dd if=./part1.image of=/dev/hda1 - to restore
    ```
* Write usb bootable from iso file:

    `dd if=./image.iso of=/dev/sdx` ( should be `sda` or `sdb` or `sdc` )

* Install common dev stuff (like `ssh`, `vim` and `mc`) missing after clean install on debian-like os:

    ```
    sudo -s
    apt-get update
    apt-get upgrade -y
    apt install -y net-tools wireless-tools apt-transport-https curl ca-certificates \
    build-essential software-properties-common python gcc g++ make subversion git \
    openssl libssl-dev openssh-client openssh-server screen vim mc
    ```

    - special only for ubuntu:

    `ubuntu-restricted-extras`

    - minimal MTA (sendmail)

    `nullmailer mailutils`

* **screen** - terminal multiplexor - keeps your terminal session on server

    - `apt install screen`

    - `screen` - start new session

    - `screen -ls` - list running sessions

    - `screen -r` - reconnect

    - `CTRL + A, D` - disconnect

    - `CTRL + A, C` - open new terminal tab

    - `CTRL + A, 0..9` - switch tab directly

    - `CTRL + A, capital K` than press `y` - to kill session

    - cool adjustment with display tabs, cpu, time - place this file on home dir `.screenrc`
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

    - Client-side fix:

        - Set appropriate env vars (`EXPORT LC_ALL=$LANG`)

        - Disable sending locale information over terminal
          (on OSX unset `Set locale environment variables on startup` in `Advanced` settings tab)

    - Server-side fix:

    ```
            apt-get purge locales
            apt install locales (locales-all)
            dpkg-reconfigure locales
            locale -a
    ```

* Install [Certbot](https://certbot.eff.org) on [nginx](http://nginx.org/ru/docs/)-based web server

    `apt install -y certbot python-certbot-nginx`

* Generate new certificates on working system with nginx

    `certbot --nginx -d example.com -d www.example.com`

* Generate SSL certificates for domains via Certbot

    `certbot certonly --standalone -d example.com -d www.example.com`

* Update expired sertificates

    `certbot renew`

* **CI** in 1 line of code ;)
    
    `crontab -e` - to open cron jobs file editor
    
    `*/1 * * * * cd /home/user/project && /usr/bin/git pull -q origin master >/dev/null 2>&1`
    
    The periodical job to pull from master branch
    
    **YOU SHOULD USE [WEBHOOKS](https://developer.github.com/webhooks/) / [GITLAB CI](https://about.gitlab.com/product/continuous-integration/) INSTEAD!**

# APT

`dpkg --get-selections | grep foo` - find all packages by name `foo`

`dpkg-query --status foo` - info about package `foo`

`apt-get remove foo` - delete package `foo`

`apt-get autoremove` - delete all obsolete packages

`apt-get install -y gcc g++ make nodejs npm` - install list of packages in one line without confirmation

# CRON

`crontab -l` - show current cron jobs

`crontab -e` - open crontab file with default editor 

crontab example:

	```
	# m h dom mon dow user	command
	# every minute
	* *	* * * www-data wget -O - -q -t 1 http://localhost/api/cron
	# every hour
	0 * * * * cmd
	```

# SSH

* [SSH keygen](https://www.ssh.com/ssh/keygen)

* Prevent `git@gitlab.com: Permission denied (publickey).` connection error

    ```
    eval "$(ssh-agent -s)"
    ssh-add -l
    ssh-add -K ~/.ssh/id_rsa (or other file)
    ```

or just `ssh add`

[How to add new ssh key](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/#adding-your-ssh-key-to-the-ssh-agent)

* test access rights: `ssh -vT git@github.com`

* view ssh key fingerprint: `ssh-keygen -lf ~/.ssh/id_rsa.pub`

[About ssh agent](https://www.ssh.com/ssh/agent)

* To easy add existing key from this pc to host - `ssh-copy-id -i ~/.ssh/mykey user@host`

* To test key - `ssh -i ~/.ssh/mykey user@host`

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

    `ssh -N -L localhost:6379:localhost:6379 example.com` (`-L ... -L ...` to multiply number of ports)

* Mount fs via sftp

    ```
    apt install sshfs
    mkdir /media/server1
    sshfs -o allow_other,follow_symlinks,IdentityFile=~/.ssh/keyfile username@hostname:/ /media/server1
    ...
    umount /media/server1
    ```

# GIT

```
git config --global --list
git config --global user.name "John Doe"
git config --global user.email john@example.com

git init

git remote -v
git remote add

git branch

git checkout -b new_branch
git checkout other_branch
git checkout master

git branch -d localBranchName
git push origin --delete remoteBranchName

git status
git pull

git merge

git add .
git commit -m "msg"

git push -u origin master

git rm -r ObsoleteDir

git log --oneline

git checkout -- .
git reset --soft HEAD^
git reset --hard HEAD^
git revert HASHCODE
git stash
git stash list
git checkout BRANCH_WHERE_YOU_STASHED
git stash apply
git stash drop

git tag -d TAGNAME
git push origin :refs/tags/TAGNAME
```

[list of GIT commands](https://github.com/joshnh/Git-Commands)

# NODE

* [Install Nodejs](https://github.com/nodesource/distributions/blob/master/README.md)

* Install module globally - `npm i -g jslint`

* Add to package.json dependencies - `npm i -P <package>`

* Add to package.json devDependencies - `npm i -D <package>`

* Full reinstall for project - rm -rf ./node_modules && rm ./package-lock.json && npm i

* Update npm itself - `sudo npm update -g`

* List updatable - `npm outdated -g`

* Find installed foo - `npm list -g | grep foo`

* Useful npms - `pm2 serve eslint express knex`

* upgrade package.json dependencies to latest versions

   ```
   npm i -g npm-check-updates
   ncu -u
   npm install
   ```

# YARN

`npm -i -g yarn` or `brew install yarn` to install [Yarn](https://yarnpkg.com/en/)

`yarn` - bring yarn into existing npm project

`yarn install foo` - install `foo` package

`yarn remove foo` - uninstall `foo` package

`yarn dev` - run `dev` npm script

* fix `apt-get update` error `The following signatures were invalid: EXPKEYSIG 23E7166788B63E1E Yarn Packaging <yarn@dan.cx>`:

    `curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -`

# OSX

* Background services

  `launchctl list` (with ` | grep whatever`)
  
  `brew services list`

  instead of `list` use `NAME start|stop|restart` to control

* Shebang for `/usr/local/bin/*` shell scripts

    `#!/bin/sh`

    Don't forget to set execute permissions - use `chmod +x /.../bin/foo` to set it

* Screenshots

    `CMD + SHIFT + 4`

* Mount via sftp

    - Install osxfuse and sshfs:

        ```
        brew cask install osxfuse
        brew install sshfs
        ```

    - Test ssh connection:

        `ssh -i ~/.ssh/keyfile username@hostname`

    - Mount remoute share:

        ```
        mkdir /mountpath
        sshfs username@hostname:/ /mountpath
        ...
        diskutil umount force /mountpath
        ```
* Remote SSH to Mac

    - Open the Apple menu in the upper left corner of the screen, and select "System Preferences...".
     
    - Under "Internet & Wireless", select "Sharing".
     
    - In the left column of services, enable "Remote Login".
     
    - Highlight the "Remote Login" service and enable access for the users you would like to have SSH access.
     
    - You can select all users, or specific users by selecting "Only these users:" and adding the appropriate users by clicking "+".
     
    - Take note of the command displayed underneath the words "Remote Login: On" in the upper middle part of the screen.
     
    - Write this command down as you will need it to log in from a different system.
     
    - If your firewall is enabled (which it is by default), you may need to restart the firewall to allow SSH communications to pass through port 22.
     
    - Open "System Prefrences", click "Security", and restart the Firewall.
     
    - Test that the firewall is not blocking SSH access by going to a different system and entering the ssh login command in step 6 above.
     
    - If you cannot login, restart the firewall or reboot.


# ESLINT

```
/* eslint-disable no-undef */
...
/* eslint-enable no-undef */
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

    `select from_unixtime(2147483647)`
    =>
    `2038-01-19 05:14:07` - 32-bit time_t limit (2038-year timestamp overflow)

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
    
* bitcoin

```
sudo add-apt-repository ppa:bitcoin/bitcoin
sudo apt update
sudo apt install bitcoin-qt bitcoind
bitcoin-qt
```

* [reset root password](https://linuxconfig.org/how-to-reset-root-mysql-password-on-ubuntu-18-04-bionic-beaver-linux)

* Useful links:

    * [GIT](https://git-scm.com/downloads)
    
    * [Docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/), [Docker compose](https://docs.docker.com/compose/install/)

    * [Sublime text editor](https://www.sublimetext.com/3), [vue highlight](https://github.com/vuejs/vue-syntax-highlight)
    
    * [VSCode](https://code.visualstudio.com/docs/setup/setup-overview), [npm-scripts](https://marketplace.visualstudio.com/items?itemName=traBpUkciP.vscode-npm-scripts), [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur), [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode), [Gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
    
    * [Vue-cli](https://github.com/vuejs/vue-cli), [Vue-devtools](https://github.com/vuejs/vue-devtools)
    
    * [Texture packer](https://www.codeandweb.com/texturepacker)
    
    * [Tiled map editor](https://www.mapeditor.org/)
    
    * [App manifest](https://app-manifest.firebaseapp.com/)
    
    * [GIF converter](https://ezgif.com/)
    
    * [MakeAppIcon](https://makeappicon.com/)
    
    * [Favicon.io](https://favicon.io/), [Real Favicon Generator](https://realfavicongenerator.net/)
    
    * [Vector editor](https://vectr.com/)
    
    * [CSS grid generator](https://cssgrid-generator.netlify.com/)
    
    * [PDF converter](https://online2pdf.com)
    
    * [HTML formatter](https://www.freeformatter.com/html-formatter.html)
    
    * [CSS Code Beautifier](http://www.codebeautifier.com/)
    
    * [Build your own X](https://github.com/danistefanovic/build-your-own-x/blob/master/README.md)
    
    * [TERA smart money](https://sourceforge.net/projects/tera/)

/usr/local/bin/tera

```
#!/bin/sh

if pgrep -f "run-node.js" > /dev/null
then
  pm2 show run-node.js
else
  cd /root/wallet/Source/ && pm2 start run-node.js
fi
```
