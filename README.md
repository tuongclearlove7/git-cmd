<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://coveralls.io/github/nestjs/nest?branch=master" target="_blank"><img src="https://coveralls.io/repos/github/nestjs/nest/badge.svg?branch=master#9" alt="Coverage" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Auth

```bash

- Xem tất cả các nhánh từ xa
$ git branch -r

- Xem tất cả các nhánh cục bộ và từ xa
$ git branch -a

- Xem tất cả các nhánh cục bộ
$ git branch

- Buộc xóa nhánh
$ git branch -D <branch name>

- Xóa nhánh từ xa
$ git push origin --delete <branch name>

- Tạo nhánh mới
$ git checkout -b <branch name>

- Chuyển sang nhánh khác
$ git checkout <branch name>

- Xem các thay đổi vừa sửa trong các file
$ git checkout

- Undo lại commit đã đẩy lên
$ git revert HEAD

- Undo lại commit đã đẩy lên theo id
$ git revert 697f8fa

- Undo lại commit vừa commit
$ git reset --soft HEAD~1

- Xóa commit đã đẩy lên
$ git reset --hard ae8e8637^
$ git push origin HEAD --force

- Kiểm tra các commit 
$ git reflog

- Undo lại commit vừa bị xóa
$ git reset --hard ae8e8637
$ git push origin HEAD --force


# Setting passport package
$ npm install --save @nestjs/passport passport passport-local
$ npm install --save-dev @types/passport-local

# Create module
$ nest g module auth
$ nest g controller auth --no-spec
$ nest g service auth --no-spec
$ nest g resource users

# Create module in module
$ nest g resource kitchenLocators/manager-kitchen-locator

# Setting package
npm i @nestjs/mongoose mongoose
npm install @nestjs/jwt --save
npm i --save @nestjs/config
npm i bcryptjs --save 
npm i --save class-validator class-transformer
npm i passport-jwt --save
npm install @types/passport-jwt
npm i bcrypt @types/bcrypt
npm i jsonwebtoken @types.jsonwebtoken
npm i cookie-parser && npm i -D @types/cookie-parser

```

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://kamilmysliwiec.com)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](LICENSE).
