# Go Hugo Starter Project
### Installing GoLang

**You can see the official documentattion on thise link [link](https://golang.org/dl/)**

- Download the archive and extract it into /usr/local, creating a Go tree in /usr/local/go. For example:
    ```
    ~$ cd ~/Downloads
    ~$ wget -c https://storage.googleapis.com/golang/go1.7.3.linux-amd64.tar.gz
    ```

    ```
    ~$ tar -C /usr/local -xvzf go1.7.3.linux-amd64.tar.gz
    ```
- (Typically these commands must be run as root or through sudo.)

    Add /usr/local/go/bin to the PATH environment variable. You can do this by adding this line to your /etc/profile (for a system-wide installation) or $HOME/.profile:
    ```
    ~$ export PATH=$PATH:/usr/local/go/bin
    ```

### Install Hugo

[Hugo installation](https://gohugo.io/getting-started/installing/)
---------------

### Estructura de organizacion
- [Hugo organization oficial doc link](https://gohugo.io/content-management/organization/)
    cada carpeta que se coloque dentro de la carpeta `content` sera interpretada como una nueva seccion o pagina
    por ejemplo:
    ```php
    .
    └── content
        └── about
        |   └── _index.md  // <- https://example.com/about/
        ├── posts
        |   ├── firstpost.md   // <- https://example.com/posts/firstpost/
        |   ├── happy
        |   |   └── ness.md  // <- https://example.com/posts/happy/ness/
        |   └── secondpost.md  // <- https://example.com/posts/secondpost/
        └── quote
            ├── first.md       // <- https://example.com/quote/first/
            └── second.md      // <- https://example.com/quote/second/
    ```
---------------

### hugo comands
**development command**
```
~$ hugo -D 
```
**Build command**

al correr este comando se creara la carpeta `public` con todos los contenidos de la web

**nota**: _siempre ante de volver a correr el comando build devese borrar la carpeta public_
```
~$ hugo
```
---------------
### Deploy Site Examples
in the official documentation exist an exampole about the way deploy the sites on differents hosting

[Hugo official deploy doc LINK](https://gohugo.io/hosting-and-deployment/)

---------------
### Hugo themes

- [Hugo themes](https://themes.gohugo.io)
- [Hugo bulma theme](https://themes.gohugo.io/bulma/)
