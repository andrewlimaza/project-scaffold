# 10up Project Scaffold

The 10up Project Scaffold is a command line tool to quickly initialize a started theme or plugin for your new project. It adheres to all 10up's best practice coding standards and has been reviewed for security, performance, and scalability. This project is aimed specifically at the work that 10up does, but we welcome all community contributions.

If you have an update for the theme or plugin that is generated, please submit those issues or pull requests with the associated repository:

[View the theme repository](https://github.com/10up/theme-scaffold)

[View the plugin repository](https://github.com/10up/plugin-scaffold)

## Set Up from Github

1. Clone the [repository]( https://github.com/10up/project-scaffold) locally
2. Run `cd project-scaffold`
3. Run `npm install`
4. Run `npm link` to make the `create-10up` command global

## Setup from npmjs.com

`npm install create-10up -g`

## Run Globally
`cd <your-project-directory>`

`create-10up <project-type> <project-name>`

### Example Usage
`create-10up theme human-theme-name`

`create-10up plugin human-plugin-name`
