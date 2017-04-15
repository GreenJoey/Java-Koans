# Java Koans

This is the solutions  to the [Java Koans](https://github.com/matyb/java-koans).


Running Instructions:
=====================
* Within it you'll find:
    * *koans*: this directory contains the application and its lessons, it is all that is needed to advance through the koans themselves and **it can be distributed independently**
    * *lib*: this directory contains the code the koans engine is comprised of and built with
    * *gradle*: wrapper for build library used to build koans source, setup project files in eclipse/idea, run tests, etc. you probably don't need to touch anything in here
* Change directory to the koans directory: ```cd koans```
* Run in the shell ```./run.sh```


Something's wrong:
==================
* If the koans app is constantly timing out compiling a koan, your computer may be too slow to compile the koan classes with the default timeout value. Update the compile_timeout_in_ms property in koans/app/config/config.properties with a larger value and try again.
