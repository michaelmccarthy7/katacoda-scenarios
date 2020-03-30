### No Inheritance
We can tidy up the code by creating a new parent class dor any shared properties:

```python
class stockItem:
    description = ""
    price = 0.0
    
class grocery(stockItem):
    weight = 0.0
    
class mineral(stockItem):
    volume = 0.0
    
class newspaper(stockItem):
    publisher = ""
    
```{{copy}}