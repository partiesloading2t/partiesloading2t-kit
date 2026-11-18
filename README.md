# partiesloading2t-kit

Count lines, words and characters, with totals.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m partiesloading2t_kit.cli --help
```

```python
from partiesloading2t_kit.core import Partiesloading2tTool

tool = Partiesloading2tTool()
print(tool)
```

## Layout

```
partiesloading2t_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 partiesloading2t
