# sample code

```python
from random import randint

def num_picker(num):
    strat_num = 1
    if num >= 1 and num < 45:
        end_num = num + 1
        result = randint(1, num+1)
        return result
    else:
        return False
```

