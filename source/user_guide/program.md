# Python programming

## PyProgressBar Class

The PyProgressBar provides a progress bar.

### Public Functions

|  Returns   |    Function      | Note |
|  ----  | ----                     | ---- |
| None  | **reset**(self, maximum = 100) | Reset progress.|
| None  | **setValue**(self, val, msg = None) | Set current value |

### reset(self, maximum = 100)
Reset the progress bar. The progress bar "rewinds" and shows no progress.

#### Args

- `maximum` (int): This parameter holds the progress bar's maximum value.

#### Example

```python
from PyCore import PyProgressBar

progress = PyProgressBar()
progress.reset()
```

### setValue(self, val, msg = None)
This function holds the progress bar's current value

Attempting to change the current value to one outside the minimum-maximum range has no effect on the current value.

#### Args

- `val` (int): This parameter holds the progress bar's current value.
- `msg` (str): This parameter holds the descriptive text shown with the progress bar.

#### Example

```python
from PyCore import PyProgressBar

progress = PyProgressBar()
progress.reset()
progress.setValue(0,'start xxx')
progress.setValue(10,'step xxx')
progress.setValue(100,'finish xxx')
```