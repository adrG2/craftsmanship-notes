# Craftsmanship notes

- [Clean code](https://github.com/adrG2/software-craftsman-notebook/tree/main/clean-code)

- [Java](https://github.com/adrG2/software-craftsman-notebook/tree/main/java)

  - [Effective Java](https://github.com/adrG2/software-craftsman-notebook/tree/main/java/_effective-java-book)




# Tools

## Comando para ver los ficheros más modificados de un proyecto

```bash
git log --pretty=format: --name-only | sort | uniq -c | sort -rg | grep '.ts' | head -10
```


