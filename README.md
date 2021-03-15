## How To Use

### 1. check node version, the most recent version is recommended. ```Node 14.15.4 LTS``` has been well tested. Or you may encounter bugs issued by Node, e.g. [#13](https://github.com/padlocal/wechaty-puppet-padlocal/issues/13)
```
node --version // >= v14.0.0
``` 

### 2. install node modules
After cloning the repo, change current directory to repo's root folder:

RUN: `yarn install` or `npm install`


### 3. apply padlocal token
**Contact [admin](mailto:oxddoxdd@gmail.com) to apply PadLocal token.**

In your terminal, do:
```
export WECHATY_PUPPET_PADLOCAL_TOKEN=puppet_padlocal_xxx
```
before next step.

### 4. try the demo
RUN: `yarn run demo` or `npm run demo`

```
$ yarn run demo
$ ./node_modules/.bin/ts-node main.ts
[Fri Oct 09 2020 00:00:00] [LOG]    TestBot started.
[Fri Oct 09 2020 00:00:00] [LOG]    TestBot Contact<${YOUR ACCOUNT NICK NAME}> login
[Fri Oct 09 2020 00:00:00] [LOG]    TestBot ready.


# bot is ready, all setup work has been done.
# when new message comes, following logs will be printed.

[Fri Oct 09 2020 00:00:01] [LOG]    TestBot on message: Message#Text ...
```
