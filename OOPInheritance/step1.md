### No Inheritance
If we were to use classes without inheritance for the following example the classes might look like this:


<pre class="file" data-filename="test.py" data-target="replace">
class grocery:
    description = ""
    price = 0.0
    weight = 0.0
        
    def __init__(self,d,p,w):
        self.description = d
        self.price = p
        self.weight = w
    
class mineral:
    description = ""
    price = 0.0
    volume = 0.0
    
    def __init__(self,d,p,v):
        self.description = d
        self.price = p
        self.volume = v
    
class newspaper:
    description = ""
    price = 0.0
    publisher = ""
    
    def __init__(self,d,p,pb):
        self.description = d
        self.price = p
        self.publisher = pb
    
    
newItem = mineral("Coke", 1.80, 500.0)
print (newItem.description)
    
</pre>


copy the code to the editor and run it by typing 

<pre>
python test.py 
</pre>
in the terminal.
