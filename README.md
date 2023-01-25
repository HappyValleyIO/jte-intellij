# jte-intellij

## NOTE

This is a hacked together workaround for this issue: https://youtrack.jetbrains.com/issue/WEB-59150

It sets the suffixes for JTE templates to `.jte.html` and `.kte.html`. Note, to make this work you'll need to ensure
that templates are copied as a part of your build process to drop the `.html` suffix.

To install, download the artifact (or run gradle buildPlugin) and install from disk in intellij.

## Regularly Scheduled Programming

IntelliJ plugin for <a href="https://github.com/casid/jte">jte template files</a>.

Download the latest version at the <a href="https://plugins.jetbrains.com/plugin/14521-jte">JetBrains plugin
repository</a>

<img alt="jte in IntelliJ" src="https://github.com/casid/jte/raw/master/jte-intellij.gif" style="max-width:100%;" width="50%">
