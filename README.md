<p align="center">
<img width="150" height="150" alt="Lovely Sim Racing" src="docs/images/lr-logo-small.png">
</p>

<h1 align="center">Lovely Car Classes</h1>

<p align="center">
A comprehensive list of Car Class name Shorthands for use in Sim Racing Games.
</p>

---

# How To

All you need to do is fetch the url `https://raw.githubusercontent.com/Lovely-Sim-Racing/lovely-car-classes/main/data/car-classes.json`. Car Classes are simple Label:Value pairs.



## Contributing
To maintain properly formatted files, I've implemented - and require - a `pre-commit` script, that will prettify the JSON files and thus properly track changes to them.

### 1. Install Pre-Commit Hook
Before you can run hooks, you need to have the pre-commit package manager installed. You can do so by following the instructions on the [official pre-commit website](https://pre-commit.com/#installation), or just install it using the following command:

```
brew install pre-commit
```

Homebrew not your thing? Read more on the [official pre-commit website](https://pre-commit.com/#installation).


### 2. Install Git Hook Scripts

Once installed, run `pre-commit install` to set up the git hook scripts

```
pre-commit install
```

### 3. Test & Finish
You're all set as far as tooling is concerned. Every time you make a commit, the `pre-commit` script will make sure the files are properly formatted and are prettified. 

It's usually a good idea to run the hooks against all of the files when adding new hooks (usually pre-commit will only run on the changed files during git hooks). Running `pre-commit run --all-files` will have a pass at everythig, and if all is well, you should see somthing like the below. 

```
$ pre-commit run --all-files
check json...............................................................Passed
pretty format json.......................................................Passed
```
