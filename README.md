# Programming Exercise Template

[![Build Status](https://travis-ci.com/lparolari/programming-exercise-template.svg?token=VSm1u6swXqyzsdGeq7Kp&branch=master)](https://travis-ci.com/lparolari/programming-exercise-template)

> A handy latex template for programming exercises in high school.

## Installation

```
git clone git@github.com:lparolari/programming-exercise-template.git exercise-name
cd exercise-name
rm -rf .git .travis.yml LICENSE README.md
```

## Usage

- **Edit** `exercise.tex`.
- **Run** `make pdf`.

### FYI

The directory is composed by a bunch of source files.

- `exercise.tex`, the main file where. Here you can write the exercise text.
- `exerciseconfig.tex` contains the configurations for the main file: here you can tweak some configurations to meet your requirements. Basically it is needed for _on-the-fly_ macros and utilities.
- `packages.tex` contains all packages needed by the main file.
- `macros.tex` where you can find some useful commands and macros (more information [here](https://github.com/lparolari/latex-macros)).
- `prooftree.tex`, a handy packages for creating prooftrees (needed by `macros.txt`).

## Example

You can see how the template looks like in releases: see the last release [here](https://github.com/lparolari/programming-exercise-template/releases).

## Author

Luca Parolari <<luca.parolari23@gmail.com>>

## License

See [LICENSE](LICENSE) file.
