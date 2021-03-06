# Angular2 Tutorial [![Build Status][travis-image]][travis-url]

This repository is an example application for angular2 tutorial.

[Demo](https://micropost.hana053.com/)

* Ahead-of-time compilation
* Lazy Loading
* Preloading 

## Getting Started

Prepare backend app.

```
git clone https://github.com/springboot-angular2-tutorial/boot-app.git
cd boot-app
mvn spring-boot:run
```

Serve frontend app by webpack-dev-server.

```
npm install -g yarn@">=0.16.0"
yarn install
yarn start
open http://localhost:4200
```

Testing.

```
yarn test
```

Production build.

```
yarn run build:prod
yarn run server:prod
open http://localhost:4200
```

## Tutorial

Under construction...

## Related Projects

* [Spring Boot app](https://github.com/springboot-angular2-tutorial/boot-app)
* [Android app](https://github.com/springboot-angular2-tutorial/android-app)
* [Server provisioning by Ansible](https://github.com/springboot-angular2-tutorial/micropost-provisionings)
* [Infrastructure by Terraform](https://github.com/springboot-angular2-tutorial/micropost-formation)

## Credits

* [Rails tutorial](https://github.com/railstutorial/sample_app_rails_4)
* [angular2-webpack-starter](https://github.com/AngularClass/angular2-webpack-starter)

## License

[MIT](/LICENSE)

[travis-url]: https://travis-ci.org/springboot-angular2-tutorial/angular2-app
[travis-image]: https://travis-ci.org/springboot-angular2-tutorial/angular2-app.svg
