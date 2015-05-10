# VHOST

> Making virtual host maniputation tasks more easier


## Instalation ##


Clone this repository and add in ```custom/plugins``` folder

```bash
$ git clone git://github.com/willmendesneto/vhost.git ~/.oh-my-zsh/custom/plugins/vhost
```

Open your `.zshrc` file and load `vhost` plugin.

```bash
...
plugins=( <your-plugins-list>... vhost)
...
```

After this, restart your terminal and vhost plugin is configurated in you CLI.


## Commands ##


### ls

List all virtual hosts in `/etc/hosts` file

```bash
vhost ls
```


### add

Add a new virtual host in `/etc/hosts` file

```bash
vhost add <ip> <host>
```


### rm

Add a new virtual host in `/etc/hosts` file

```bash
vhost rm <ip> <host>
```


## Author

**Wilson Mendes (willmendesneto)**
+ <https://plus.google.com/+WilsonMendes>
+ <https://twitter.com/willmendesneto>
+ <http://github.com/willmendesneto>

New features comming soon.
