# Craftsmanship notes

## Index

- [Clean code](https://github.com/adrG2/software-craftsman-notebook/tree/main/clean-code)

- [Java](https://github.com/adrG2/software-craftsman-notebook/tree/main/java)

  - [Effective Java](https://github.com/adrG2/software-craftsman-notebook/tree/main/java/_effective-java-book)


## Tools

### Comando para ver los ficheros más modificados de un proyecto

```bash
git log --pretty=format: --name-only | sort | uniq -c | sort -rg | grep '.ts' | head -10
```

### This git command finds the 50 hotspots of your legacy codebase:
```bash
git log --format=format: --name-only --since=12.month| egrep -v '^$' | sort | uniq -c | sort -nr | head -50
```

