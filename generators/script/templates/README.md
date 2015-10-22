# <%= appname %>

[![Build Status](https://travis-ci.org/ClaudeBot/<%= appname %>.svg)](https://travis-ci.org/ClaudeBot/<%= appname %>)
[![devDependency Status](https://david-dm.org/ClaudeBot/<%= appname %>/dev-status.svg)](https://david-dm.org/ClaudeBot/<%= appname %>#info=devDependencies)

<%= scriptDescription %>

See [`src/<%= scriptName %>.coffee`](src/<%= scriptName %>.coffee) for full documentation.


## Installation via NPM

1. Install the **<%= appname %>** module as a Hubot dependency by running:

    ```
    npm install --save <%= appname %>
    ```

2. Enable the module by adding the **<%= appname %>** entry to your `external-scripts.json` file:

    ```json
    [
        "<%= appname %>"
    ]
    ```

3. Run your bot and see below for available config / commands


## Commands

Command | Listener ID | Description
--- | --- | ---
hubot hello | `hello` | what the respond trigger does


## Sample Interaction

```
user1>> hubot hello
hubot>> hello!
```
