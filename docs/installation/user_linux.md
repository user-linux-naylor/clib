## Linux Clib Installation: 

With git:

```sh
$ git clone https://github.com/clibs/clib.git /tmp/clib
$ cd /tmp/clib
$ make install
```

  Ubuntu:

  ```sh
  # install libcurl
  $ sudo apt-get install libcurl4-gnutls-dev -qq
  # clone
  $ git clone https://github.com/clibs/clib.git /tmp/clib && cd /tmp/clib
  # build
  $ make
  # put on path
  $ sudo make install
  ```

Fedora:

```sh
# install libcurl
$ sudo dnf install libcurl-devel
# clone
$ git clone https://github.com/clibs/clib.git /tmp/clib && cd /tmp/clib
# build
$ make
# put on path
$ sudo make install
```

Nix:
```sh
$ nix-env -i clib
```                                                                                                                                                                                                                            Or add to your `nativeBuildInputs`.

