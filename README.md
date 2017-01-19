


1. Building a JavaScript Development Environment
   by Cory House

   Keyword: Development environment, Boilerplate, starter kit, starter project, Seed

https://app.pluralsight.com/library/courses/javascript-development-environment/table-of-contents

Starting a new JavaScript project from scratch is overwhelming. This course provides a playbook outlining the key decisions you need to make.
Build a robust development environment that handles bundling, linting, transpiling, testing, and much more.

(1) react starter project:
http://andrewhfarmer.com/starter-project/


https://github.com/kriasoft/react-starter-kit


(2) ruanyf: http://javascript.ruanyifeng.com/

(3) angular js: awesome angular-js: https://github.com/gianarb/awesome-angularjs

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

#  Install the Tracker Library

<!-- BEGIN TRACKJS -->
<script type="text/javascript">window._trackJs = { token: 'b0608e180e834d62bb0222b1842929eb' };</script>
<script type="text/javascript" src="https://cdn.trackjs.com/releases/current/tracker.js"></script>
<!-- END TRACKJS -->

Track an Error: trackJs.track('ahoy trackjs!');

user: zhuohua's gmail
pwd: trackjs123

# Setup heroku:

(1) install heroku-cli:
  https://dashboard.heroku.com/apps
  Download heroku-cli: https://devcenter.heroku.com/articles/heroku-cli

  Verify:
    Viafouras-MBP-4:pluralsight-js-dev-env kevinwu$ heroku --version
    heroku-cli/5.6.8-9647e01 (darwin-amd64) go1.7.4

(2) login and create a heroku project
  heroku login
  heroku create

  Viafouras-MacBook-Pro-4:js-dev-env-demo-api kevinwu$ heroku create
  Creating app... done, ⬢ immense-depths-60655
  https://immense-depths-60655.herokuapp.com/ | https://git.heroku.com/immense-depths-60655.git

(3) to to url:
url: https://immense-depths-60655.herokuapp.com/

(4) bundle to heroku remote
  heroku git:remote -a immense-depths-60655

(5) push to remote server
  git push heroku master

  ...
  remote:        https://immense-depths-60655.herokuapp.com/ deployed to Heroku
  remote:
  remote: Verifying deploy... done.
  To https://git.heroku.com/immense-depths-60655.git
     1d50b3b..b6b2d92  master -> master


go to url: https://immense-depths-60655.herokuapp.com/users

(6) use surge.sh:

# http://surge.sh/
go to url: holistic-friend.surge.sh


# setup yeoman:


```
