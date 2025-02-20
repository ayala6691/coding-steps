# Coding Steps

A unified monorepo for logic problems in javascript/typescript exercises. This repo does not replace the original sites but design to make it easier to get the exercises and setup of them. Please visit the original sites.

## General Usage

1. Clone the project

```bash
git clone git@github.com:Proftit-TC/coding-steps.git
```

2. Install dependencies with yarn. It does not matter in which directory of the project.

```bash
yarn install
```

3. One time install the git hooks that run code formating before each commit.

```bash
yarn husky install
```

4. Enter the folder of the desired package and run the test.

```bash
yarn test
```

The tests can be run in `watch` mode.

```bash
yarn test:watch
```

## Contributing

1. Create a fork.
2. Make some code changes to the fork.
3. Add a commit with a new changeset file that describe the change. `yarn changeset`
4. Create a PR

## Keeping your fork up to date

1. Clone your fork
2. Add remote from original repository in your forked version:

```bash
cd into/cloned/fork-repo
git remote add upstream https://github.com/Proftit-TC/coding-steps.git
git fetch upstream
```

3. Update your fork from original repository to keep up with changes

```bash
git pull upstream main
```

4. Updated your local repository

```bash
git push
```

## Attributions

Those exercises are taken from several excellent places under several licenses.

### Exercism

> Code practice and mentorship for everyone Level up your programming skills with 3,450 exercises across 52 languages, and insightful discussion with our dedicated team of welcoming mentors. Exercism is 100% free forever.

- site - https://exercism.io/
- license - https://github.com/exercism/typescript/blob/main/LICENSE

### Project Euler

> Project Euler is a series of challenging mathematical/computer programming problems that will require more than just mathematical insights to solve. Although mathematics will help you arrive at elegant and efficient methods, the use of a computer and programming skills will be required to solve most problems.

> The motivation for starting Project Euler, and its continuation, is to provide a platform for the inquiring mind to delve into unfamiliar areas and learn new concepts in a fun and recreational context.

- site - https://projecteuler.net
- license - https://projecteuler.net/copyright

### Learn Rxjs

> Clear examples, explanations, and resources for RxJS.

- site - https://www.learnrxjs.io/
- license - https://github.com/btroncone/learn-rxjs/blob/master/LICENSE

## Tools Used

### Yarn

- https://devhints.io/yarn

### Jest

- https://devhints.io/jest

### Changeset

- https://github.com/atlassian/changesets/blob/main/docs/intro-to-using-changesets.md

### Markdown

- https://www.markdownguide.org/cheat-sheet/
