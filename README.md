*Goodness Corp*? or *Garbage Collector*? Who knows... Maybe its *Global Collection*, no its *Gone Cuties*!
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

Or *IIFE*, *JIT*, *event bubbling*, whatever... you know?

Nevermind, if you do ;) Its kick your ASs! Just remeber - GC!

Ok, well, shuffling some enother stuff...

##[ vim ]

Cut and paste:

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

##[JS]

First of all just clarify that you on a right toolchain

```
function log() {
  console.log.apply(null, Array.prototype.slice.call(arguments));
}

function dump() {
  var a = Array.prototype.slice.call(arguments), s = '';
  if (!a.length > 0) return;
  if (typeof a[0] === 'string') s += (a.shift() + '\n');
  for (var i = 0; i < a.length; i++) s += (app.util.inspect(a[i]) + '\n');
  app.fs.writeFileSync('dump.log', s);
}

function dump_to(f) {
  if (undefined === f) return;
  var a = Array.prototype.slice.call(arguments), s = '';
  if (!a.length > 1) return;
  for (var i = 1; i < a.length; i++) s += (app.util.inspect(a[i]) + '\n');
  app.fs.writeFileSync(f, s);
}

function dump_to_json(f, o) {
  if (undefined === f || undefined === o) return;
  app.fs.writeFileSync(f, JSON.stringify(s));
}

function dump_to_jsonfy(f, o) {
  if (undefined === f || undefined === o) return;
  app.fs.writeFileSync(f, JSON.stringify(o, null, 2));
}
```

Backward-loop 

```
var a = ['a','b','c']; for ( var i=a.length; i-- > 0; ) { log(a[i]) }
```

##[HTML]

Minimal pic

```<img src="data:image/gif;base64,R0lGODlhAQABAPABAP///wAAACH5BAEKAAAALAAAAAABAAEAAAICRAEAOw==">```

##[PHP]

Wooot!?

one line terminal
```php -r "echo PHP_EOL;" > eol```

internally have we equal to this?:
```String.fromCharCode(13,10)``` or just ```'\n'```

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

different operatiing systems interpret a logical newline

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

Escaped characters Sequence 	  Meaning

    \n 	        linefeed (LF or 0x0A (10) in ASCII)
    \r 	        carriage return (CR or 0x0D (13) in ASCII)
    \t 	        horizontal tab (HT or 0x09 (9) in ASCII)
    \v 	        vertical tab (VT or 0x0B (11) in ASCII) (since PHP 5.2.5)
    \e 	        escape (ESC or 0x1B (27) in ASCII) (since PHP 5.4.4)
    \f 	        form feed (FF or 0x0C (12) in ASCII) (since PHP 5.2.5)
    \\ 	        backslash
    \$ 	        dollar sign
    \" 	        double-quote
    \[0-7]{1,3} 	the sequence of characters matching the regular expression is a character in octal notation
    \x[0-9A-Fa-f]{1,2} 	the sequence of characters matching the regular expression is a character in hexadecimal notation

As in single quoted strings, escaping any other character will result in the backslash being printed too. Before PHP 5.1.1, the backslash in ```\{$var}``` had not been printed.
The most important feature of double-quoted strings is the fact that variable names will be expanded. See [string parsing](https://php.net/manual/en/language.types.string.php#language.types.string.parsing) for details.
