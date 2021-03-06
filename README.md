# hapi-ts-mongo

An application starter built on Hapi, TypeScript, and MongoDB. This is not a masterpiece by any means and has not yet been validated in production, but try it out, have fun and add do it!

## Development

* Clone down the repository.
* Install npm modules
```
npm i
```
* Run development server
```
npm run dev
```
* Write features! All features written as [Hapi plugins](https://hapijs.com/tutorials/plugins?lang=en_US) in the src/plugins directory. Make sure to export your feature plugins and add them to your src/plugins/index.ts features array
## Deployment

Build the project with the following command:
```
npm run build:ts
```
Serve built project with the following command:
```
npm run serve
```

### Prerequisites

* Node.js
* MongoDB

## Built With

* [TypeScript](https://www.typescriptlang.org/)
* [Node](https://nodejs.org/en/)
* [Hapi](https://hapijs.com/)
* [MongoDB](https://www.mongodb.com/)

## Contributing

PRs welcome :)

## License

ISC
