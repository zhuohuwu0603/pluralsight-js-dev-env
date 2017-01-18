
1. link:

http://javascript.ruanyifeng.com/


javascript常用技巧：
http://scarletsky.github.io/2015/01/26/javascript-tricks/

Building Application with React and Redux in ES6
https://app.pluralsight.com/library/courses/react-redux-react-router-es6/table-of-contents


webpack:
  https://app.pluralsight.com/library/courses/webpack-fundamentals/table-of-contents


2. EditorConfig for VSCode

Atom： 好看，插件安装方便，但是真的很卡；
Sublime：快，默认没有atom好看，插件安装还行，作者最近也开始更新了；
VS code：快，但是木有Atom好看，插件少。

https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig

ext install EditorConfig

package.json sample: https://gist.github.com/coryhouse/29bd1029b623beb4c7f79b748dcba844

```python
    cmd + P: install command
    control + ` : open terminal

    npm install


# install nsp package: run security check if a package has security issue
    npm install --global nsp
    cd app_dir
    nsp check : check vulnerabilities


# install localtunnel
    npm install localtunnel -g
    lt --port 3001

    #subdomain
    lt --port 3001 --subdomain zhuohua

    https://zhuohua.localtunnel.me

# install now
    npm install -g now
    create start script:
    now


# npm run security-check
    npm run security-check

# npm run share
    npm run share

# npm-run-all --parallel security-check open:src
    npm start
    npm start -s : silent

# --parallel for share:
    npm run share
    "share": "npm-run-all --parallel open:src localtunnel"


# eslint-plugin-react

list of language compile to js: https://github.com/jashkenas/coffeescript/wiki/List-of-languages-that-compile-to-JS
webpack.config.dev.js sample: https://gist.github.com/coryhouse/d611e83e432f3ae65cc46ebb9b599930

https://gist.github.com/coryhouse/d611e83e432f3ae65cc46ebb9b599930

# .eslintrc.json file for "Building a JavaScript Development" Pluralsight course
https://gist.github.com/coryhouse/61f866c7174220777899bcfff03dab7f

npm start -s

#Unit Test
  npm test


# schema
  https://gist.github.com/coryhouse/300ed803148caaf9d4f3f45d1a03874d


# generate mock data
  npm run generate-mock-data

# start mockapi
  npm run start-mockapi
  open browser, and type in: http://localhost:3002/users


# react example
  https://github.com/coryhouse/react-slingshot

# travis ci build:
  https://travis-ci.org/zhuohuwu0603/pluralsight-js-dev-env

# gitlab ci build: failed
  https://gitlab.com/zhuohuawu/pluralsight-js-dev-env/commit/1cf906cae3fb8a1261161093499771ae82da5a23

```
