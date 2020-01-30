# piplus

Python Package Installer Plus

## Installing

Install and update using [pip]:

```text
pip install -U piplus
```

## A Simple Example

```python
from piplus import piplus

# update pip
piplus().update()

# update flask
piplus('flask').update()

# update requires
piplus('flask').requires().update()

# update flask and requires
piplus('flask').update().requires().update()
```

[pip]: https://pip.pypa.io/en/stable/quickstart/
