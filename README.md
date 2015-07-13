# tern-fetch

[fetch][] definition file for TernJS.

## Installation

Use npm install, take Vim for example:

    cd .vim/bundle/tern_for_vim
    npm i tern-fetch

Then add `fetch` in `.tern-project` lib part:

    {
      "libs": [
        "fetch"
      ]
    }

## Known Issue

Current definition file's Promise resolve value is not working well.


[fetch]:https://developers.google.com/web/updates/2015/03/introduction-to-fetch
