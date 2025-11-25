API 

create_item : ne fonctionne pas
```bash
File "/app/app/services/item_service.py", line 72, in create
    item = Item(**item_data.model_dump())
```
-> Il faut mettre un type ItemCreate au paramètre et mettre le paramètre db en Depends.


Secrets présents en dur dans main.py

Imports inutiles dans main.py (ex. import os)


RUFF

```bash
Found 12 errors.
[*] 12 fixable with the `--fix` option.
```

MYPY

```bash
brief-ci-cd-semantic-release-mkdocs git:(ci) ✗ uv run mypy app/   
Success: no issues found in 11 source files
```

