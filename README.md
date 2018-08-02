# React-with-redux-app-practice

> As title.

## Getting Started

>These instructions will get you a copy of the project up and running on your local >machine for development and testing purposes. See deployment for notes on how to >deploy the project on a live system.

1. json-server 
   ```
   // install json-server in global
   $ npm -g json-server
   
   // luanch backend API
   $ json-server --watch json-data/db.json --routes json-data/routes.json --port 5566
   ```
   Then you can call the API by Postman , the api URL like below:
   
   ```
   http://localhost:5566/api/v2/accounts
   ```
   you will get json response like :
   
   ```
   [
    {
        "id": 1,
        "name": "AAA",
        "title": "product manager"
    },
    {
        "id": 1,
        "name": "BBB",
        "title": "project manager"
    },
    {
        "id": 2,
        "name": "CCC",
        "title": "senior software engineer"
    },
    {
        "id": 3,
        "name": "DDD",
        "title": "senior software engineer"
    },
    {
        "id": 4,
        "name": "FFF",
        "title": "software engineer"
    }
   ]
   ```

   

## Prerequisites

this practice need to install the software list

1. json-server
2. live server
3. react
4. react-dom
5. webpack
6. TypeScript (Next level)
7. RxJS (Next level)
8. bootstrap (Next level)

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/RoninGAO/react-with-redux-app-practice/tags).

## Authors

* **SAM LEE** - *Initial work* - [RoninGAO](https://github.com/RoninGAO)

See also the list of [contributors](https://github.com/RoninGAO/react-with-redux-app-practice/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
