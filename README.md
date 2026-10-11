# json-flatten

Utilities for turning nested dictionaries into dotted keys and back.

## Why

The existing libraries were either abandoned or pulled in a large dependency tree.

## Install

```bash
pip install json-flatten
```

## Usage

```python
from json_flatten import jsonFlatten

result = jsonFlatten("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
