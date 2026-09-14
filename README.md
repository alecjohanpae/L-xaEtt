Test

* List
* 1
* 2
* 3
  * 3.1

```python
def run(txt):
  for i in range(1, 1 + 2**70):
    n = i
    while n > 1:
      if n % 2 == 0:
        n = n // 2
      else:
        n = n * 3 + 1
    print("All these numbers go down to 1!")
  print("You see? I know python!")
```