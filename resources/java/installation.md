# Installation


## What is available

- Java Virtual Machine (JVM)
    - A runtime component.
    - It is an interpreter which runs Java code.
- Java Runtime Environment (JRE)
    - Installed by developers and end-users.
    - To run Java applications.
    - Includes the JVM.
- Java Development Kit (JDK)
    - Development toolkit.
    - Installed by developers.
    - Includes the JRE.


## Download

- [Download](https://www.java.com/en/download/) page on the website for the runtime.

## Install with Package manager

### Install with SDKMan!

1. Install [SDKMAN!](https://sdkman.io/install)
1. Install Java. e.g.
    ```sh
    $ sdk install java 17.0.1-open
    ```

### Install on Linux with APT

Find available packages:

```sh
$ sudo apt search openjdk | less
default-jdk
  Standard Java development kit

default-jre
  Standard Java runtime

openjdk-11-jdk
  OpenJDK development kit (JDK)

[...]
```

Install one. e.g.

```sh
$ sudo apt install default-jre
```

### Install on macOS with Homebrew

#### OpenJDK

- [openjdk](https://formulae.brew.sh/formula/openjdk) - also available under `java` alias. Uses [OpenJDK][].

```sh
$ brew install openjdk
```

A message I got:

```
...

For the system Java wrappers to find this JDK, symlink it with
  sudo ln -sfn /usr/local/opt/openjdk/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk.jdk

openjdk is keg-only, which means it was not symlinked into /usr/local,
because macOS provides similar software and installing this software in
parallel can cause all kinds of trouble.

If you need to have openjdk first in your PATH, run:
  echo 'export PATH="/usr/local/opt/openjdk/bin:$PATH"' >> ~/.zshrc

For compilers to find openjdk you may need to set:
  export CPPFLAGS="-I/usr/local/opt/openjdk/include"
```

[OpenJDK]: {% link resources/java/openjdk.md %}

### Eclipse IDE for Java developers

```sh
$ brew install --cask eclipse-java
```

#### REPL

```sh
$ brew install javarepl
```
