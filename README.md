# rxpy
A fast (experimental) RX algorithm implementation in Python 3.6+ with overhead reduction based on entropy estimation via compression.

# Example usage

```python
from rx import rx
from rx.utils import plot

X = rx('/path/to/png_image.png')
plot(X, 'out.png')
```
