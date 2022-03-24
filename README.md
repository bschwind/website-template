# website-template

## Developing

Run a web server in this project directory and access `index.html` in order to test your code. There are no build steps necessary.

As an example, serving with [miniserve](https://crates.io/crates/miniserve):

```sh
$ cargo +nightly install miniserve
$ miniserve -p 1234 --index index.html .
```

## Format Code

### Install `prettier`

```sh
yarn global add prettier

or

npm install --global prettier
```

### Format

```sh
$ prettier --write .
```
