# CodeIgniter Code-Completion for SublimeCodeIntel

> The [SublimeCodeIntel](https://github.com/SublimeCodeIntel/SublimeCodeIntel) package is required.

After the installation, reload the SublimeText and open your [CI 3](https://github.com/bcit-ci/CodeIgniter) project.

Put the folder `.cc` inside the `application`.

Go to some Controller and test writing `$this->` and press `Ctrl + Shift + Space` (to run the command *code_intel_auto_complete*).

The first time you try the SublimeCodeIntel will index all your project files, then just wait some seconds...

And then, tan dannnnn:

![CodeIgniter Code-Completion for SublimeCodeIntel](https://i.imgur.com/ZGF3cod.png)

Tip: If you also press the *code_intel_auto_complete* command inside a function () the SublimeCodeIntel can show the function docs. It works with various code languages.

> On [CodeIgniter 4](https://github.com/bcit-ci/CodeIgniter4) the `.cc` folder is not necessary. SublimeCodeIntel undertand namespaces and methods return types. :)

![CodeIgniter Code-Completion for SublimeCodeIntel](https://i.imgur.com/7NYNydr.png)

References:

- [PhpStorm Code Completion to CodeIgniter + HMVC](https://github.com/natanfelles/codeigniter-phpstorm)
- [Atom PHP Environment + CodeIgniter 3 & 4](https://gist.github.com/natanfelles/a909a82936410c8ddcd917b8528faeeb)
