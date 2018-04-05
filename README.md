# Essentia-Sia-API

API bindings for [Sia decentrilized storage](http://sia.tech/).
Provides easy to use object-property syntax.

## Installation

`pip install essentia-sia-api`

## Example usage

```python
from sia.sia import Sia

sia = Sia()
sia.daemon.get_version()
```
