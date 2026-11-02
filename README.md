# AI Engineer Portfolio

Projects and exercises from Ahmed's self-directed AI engineer study path, written in Python; each folder has its own README with the problem, the approach, how to run it and its tests.

## Contents

### Other work

| Item | What it shows |
| --- | --- |
| [Publish check (v27.1.1 test)](_test/publish-check-v27-1-1/) | A throwaway item that checks the v27.1.1 publish task; it will be deleted. |

## How to run any item

```
cd <folder>
pip install -r requirements.txt
python main.py
pytest
```

Items with a pyproject.toml use `uv sync` and `uv run pytest` instead.

Every item was written while studying; each README states which checks pass.
