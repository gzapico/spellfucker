Spellfucker 
============
Yet another text obfuscator and the biggest enemy of the spellchecker

Why?
=========

Text obfuscation is not about changing "a" to "à" as it becomes revertable easily (like we see at obfuscator.uo1.net). Spellfucker's method uses random replacements which makes the reverting process more difficult. The cool thing is that the text still stays readable.

Todo
===========

To make Spellfucker even more awesome, some help is needed:

- Not all patterns have more than 1 replacements, which makes them still easily revertable.
- The algorithm is not performance-wise optimized yet.
- The library is not organized according to latest best practices.
- Some words are still difficult to read.
- We can find much more cool patterns.

Usage
===========

Get the library at **build/spellfucker** and include it into Browser or NodeJS application.

Call:

```const result = spellfucker("your string of text");```

Get a result:

```console.log(result); // returns something like "jor stryngue hoph thexd"```

NPM package is coming... Enjoy!