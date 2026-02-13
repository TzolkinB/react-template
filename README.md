## Historical Note (2026)
This was my first React boilerplate from 2019-2020. I'm archiving it as the 
ecosystem has moved to Vite/Next.js. Keeping it for historical reference.

For modern React scaffolding, I now recommend:
- Vite: `npm create vite@latest`
- Next.js: `npx create-next-app@latest`

# react-template
React template to quickly scaffold new apps.

## Dev Client Clone & Installation
Clone and rename the react-template repo:

    git clone git@github.com:TzolkinB/react-template.git new_repo_name
    * don't forget to add the .gitignore and .babelrc files

Set up remote as usual:

    git remote add origin git@github.com:TzolkinB/(new_repo_name).git
    // check that remote url is correct
    git remote --verbose
    // if it is not correct
    git remote set-url origin (correct repo url)
    git push -u origin master

Then install all of the npm dependencies:

    $ npm install

## Usage
To start the client in development run:

    $ npm start

This command will open a new window running at a default port of 4280 in your browser at
[http://localhost:4280](http://localhost:4280/).

## Versions
| Package | Version |
| --- | --- |
| react | ^16.10.2 |
| react-dom | ^16.10.2 |
| react-redux | ^7.1.1 |
| react-router | ^5.1.2 |
| redux | ^4.0.4 |
| webpack | ^4.28.0 |
