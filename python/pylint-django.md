[Ir para Python](python.md)

# VS Code + PyLint + Django

## Resolver "Class X has no 'objects' member"

1. Instale o [pylint-django](https://pypi.org/project/pylint-django/) com o comando: `pip install pylint-django`

2. Abra as configurações do seu VS Code (arquivo settings.json)

> **Como mudar configurações no VS Code?**
>
> use o atalho <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> e busque por "Settings" e escolha a opção da imagem abaixo:
> 
> ![vs-code-pylint-docstrings](/assets/vs-code-pylint-docstrings.png)

3. Inclua a opção:

```
"python.linting.pylintArgs": [
        "--load-plugins=pylint_django"
    ]
```