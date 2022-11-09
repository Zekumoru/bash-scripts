# Personal Bash Scripts

This is where I put my bash scripts which help me automate mundane tasks.

## Commands

### Create Project HTML (cphtml)

```bash
cphtml <project-name> [ --skip | -s ]
```

Creates a new project/folder which automatically sets up `webpack` (including `webpack-dev-server`, `html-webpack-plugin`, etc.), `eslint`, and `prettier`.

#### Parameters

`<project-name>` denotes the project's name and its folder.

`--skip` or `-s`, if this option is supplied, it skips the ESLint's prompt.

<br>

### Create PlayGround (cpg)

```bash
cpg <project-name> [ <title> ]
```

Creates a new project in `$HOME/repos/playground` which includes a basic setup: `index.html`, `script.js`, and `styles.css`.

`$HOME/repos/playground` is a folder that should be connected to a GitHub repository hence there's no need to initialize `git` for every project.

#### Parameters

`<project-name>` denotes the project's name and its folder.

`<title>` is an optional argument which appears as the title of the HTML template document.

> This command needs the directory `$HOME/repos/playground`. If that directory does not exists, you need to create it first.

<br>

### Testing Bash Features (testing_bash_features)

```bash
testing_bash_features [ ...arguments ]
```

A dummy script to test out how bash scripting works.

#### Parameters

`...arguments` depends on what is currently being tested.
