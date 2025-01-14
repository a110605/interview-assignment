<h1>Cube Interview Assignment</h1>

Cube Interview Assignment

- is built in ReactJS with [@carbon/react](https://carbondesignsystem.com/developing/frameworks/react/) UI toolkit. 
  - refer [@carbon/react component storybook](https://react.carbondesignsystem.com/?path=/story/components-tile--default) for more details.
- use Express framework as web server and also for APIs development.

## Requirement

Please make sure your development env has met the following requirements before you start:

| Dependency |   Version   |
| ---------- | :---------: |
| Node       | >= v12.13.0 |
| YARN       | >= v1.22.19 |

## Quick Start

```bash
$ git clone git@github.com:bigstack-oss/interview-assignment.git
$ yarn
```

### Running app for development

```bash
$ yarn dev
```


Open browser with http://localhost:3001/

![image](docs/screenshot.png)

### Code linting

```bash
$ yarn lint 
or 
$ yarn lint:fix
```

### Environment Variables

`env` and `dotenv-expand` packages are used in conjunction with `webpack.DefinePlugin` plugin for managing environment variables. 

The entire logic can be found in `./env.config.js` file. The .env file is named and loaded based on the defined `process.env.NODE_ENV` value:

| File name          | NODE_ENV    | In Source Control |
| ------------------ | ----------- | :---------------: |
| `.env.development` | development |        Yes        |
| `.env`             | production  |        Yes        |

## License

MIT
