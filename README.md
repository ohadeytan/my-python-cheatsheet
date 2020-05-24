# Basics

### Main 
```python
def main():
    pass

if __name__ == "__main__":
    main()
```

### Dict with default values
```python
from collections import defaultdict
d = defaultdict(int)
d['key'] += 1 # d['key'] == 1
d = defaultdict(list)
d['key'].append(1) # d['key'] == [1]
```
