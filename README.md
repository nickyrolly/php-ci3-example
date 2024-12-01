## Description

CodeIgniter is an Application Development Framework - a toolkit - for people who build web sites using PHP. Its goal is to enable you to develop projects much faster than you could if you were writing code from scratch, by providing a rich set of libraries for commonly needed tasks, as well as a simple interface and logical structure to access these libraries. CodeIgniter lets you creatively focus on your project by minimizing the amount of code needed for a given task.


However, we know that CodeIgniter 3 is now very old and has been abandoned by its maintainers. Therefore, dPanel is working to assist developers who still have a CodeIgniter 3 codebase by providing good support for their application operations, making it easy to duplicate.

Because once the operational processes of this legacy application are covered by an automated system, we can focus more on more productive tasks. We might even start migrating our codebase to newer, more secure technologies if needed.


### Prerequisites
- php-fpm 8.3.13
- go 1.22.7

### Development

To run this application in development, make sure the two binaries above are available. Then, follow the steps below (Linux / MacOS):
- Open 2 terminals and navigate to this repository in the root directory.
- In the first terminal, run the command: `./scripts/run-fpm-dev.sh`
- In the second terminal, run the command: `./scripts/run-dev.sh`

Congratulations, your application can be accessed at [localhost](http://localhost:8081/blog). If you want to change the settings, please check inside the "scripts" folder.

### Todo
- [ ] Build binary [golang php-dev-server](https://github.com/devetek/php-dev-server) multi platforms support
- [ ] Create development single command (golang fork and daemon)
