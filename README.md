# myGit 
My implementation of git made using Python

commands working so far :

1. init
2. hash-object
3. cat-file
4. write-tree
5. read-tree
6. commit
7. checkout
8. tag

I shall update the readme as I add features :)

### Tag Command Usage:

- `mygit tag`: Lists all existing tags.
- `mygit tag <tag-name> <commit-hash>`: Creates a new lightweight tag. If `commit-hash` is not given, defaults to HEAD.
- `mygit tag -a <tag-name> <commit-hash> -m 'Tagging message'`: Creates a new annotated tag. If `commit-hash` is not given, defaults to HEAD.
- `mygit checkout <tag-name>`: Checks out the commit with that tag.
- `mygit tag -d <tag-name>`: Deletes the tag with `tag-name`.

## Installation Instructions :

```
$ git clone git@github.com:acmpesuecc/myGit.git
$ cd myGit
$ pip install --editable .
```

### Usage :

```
$ mygit --help
```

## Contributing

We welcome contributions! Please see [CONTRIBUTING.md](https://github.com/acmpesuecc/myGit/blob/master/CONTRIBUTING.md) for guidelines on how to contribute to this project.

## License

This project is licensed under the GNU GPL v3 License. See the LICENSE file for more details.