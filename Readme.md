# electro installer

> A command line tool to create new *Electro framework* projects

## Installation

#### Runtime requirements

- Bash >= v3
- Composer

#### Installing Composer

You need [Composer](http://getcomposer.org) both to install this tool and to be able to create *Electro framework* projects. So, before proceeding, you will need to make sure you have Composer installed on your machine.

#### Installing the tool

Open a terminal window and run the following command:

```bash
composer global require electro/installer
```

This will install the tool globally, so you may access it from the terminal on any directory.

> Make sure you have the path to the global Composer-installed binaries configured on your `$PATH` environment variable, otherwise you'll not be able to run the `electro` command after installation.
>
> You may set the `$PATH` on several places, such as the `~/.profile` or `~/.bash_profile` files. You should have a line similar to this one: 
>```bash
>PATH="~/.composer/vendor/bin:$PATH"

##### Speeding up Composer

The installation process will also install [Prestissimo](https://github.com/hirak/prestissimo) globally, which is a Composer plugin that speeds up Composer installations and updates.

This will reduce the time it takes to create a new **electro** project using this tool.

> The plugin is also useful beyond the use case of this tool; it will improve Composer's performance globally, so you'll see its benefiits with any other project on your machine.

## Usage

On the parent folder, where the new project folder will be created, issue the **electro create *project-name*** command on your terminal.

For example, this will install a working Electro prototype project into the `your-project-name` folder:

```bash
electro create your-project-name
```

There are some additional command-line options that you may specify. You can find out more about them by typing:

```bash
electro
```

It will display inline documentation for the tool.

## Update

At some point in the future, you may need to update this tool to a newer version, to take advantage of bug fixes or new features, or to remain compatible with a newer version of Electro.

You can use the tool itself to check for updates and, if any is available, automatically update itself. 

Just type:

```bash
electro self-update
```

## License

The Electro framework is open-source software licensed under the [MIT license](http://opensource.org/licenses/MIT). See the LICENSE file.

**Electro framework** - Copyright &copy; Cláudio Silva and Impactwave, Lda.
