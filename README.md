## Published at https://keguigong.org/

[![Build Status](https://travis-ci.org/keguigong/www.svg?branch=master)](https://travis-ci.org/keguigong/www)
[![npm version](https://badge.fury.io/js/gatsby.svg)](https://badge.fury.io/js/gatsby)


## Branches
 - `master` : source code of the page.
 - `gh-pages` : static build files generated by Travis CI.
 - `old` : back-up files of the older page.

## Quick start

1.  **Configure packages**

    Configure the packages with `yarn`.

    ```sh
    cd www/
    
    yarn install
    ```

2.  **Start developing.**

    Preview gatsby site at `http://localhost:8000`.
    
    Check the graphQL at `http://localhost:8000/___graphql`.

    ```sh
    gatsby develop
    ```

3.  **Start building.**

    Build this page with the command then the build files will be deployed in `./public` folder.

    ```sh
    gatsby build
    ```
4. **Preview the build versions.**

    After you completing the build, use this command to preview the build version of your site.

    ```sh
    gatsby serve
    ```

## What's inside?

A quick look at the top-level files and directories you'll see in a Gatsby project.

    .
    ├── src/
    ├── static/
    ├── .travis.yml
    ├── .gitignore
    ├── gatsby-browser.js
    ├── gatsby-config.js
    ├── gatsby-node.js
    ├── gatsby-ssr.js
    ├── LICENSE
    ├── package-lock.json
    ├── package.json
    └── README.md
