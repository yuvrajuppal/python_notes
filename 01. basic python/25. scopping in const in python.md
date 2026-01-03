```python
class Const:
    def __setattr__(self, name, value):
        if hasattr(self, name):
            raise TypeError(f"Can't reassign const '{name}'")
        super().__setattr__(name, value)

const = Const()
const.hello = 19
print(const.hello)  # 19
# const.hello = 20  # TypeError!
```
