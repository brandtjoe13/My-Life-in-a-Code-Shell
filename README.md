#### Block Code

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.

```
def greatest_common_divisor(x,y):
    print "For", x, "and", y,","  
    r=x%y
    while r>0:
        r=x%y
        if r ==0: 
            print "the greatest common divisor is", y,"."
        else:
            q=y
            x=q
            y=r

greatest_common_divisor(1071,1029)
greatest_common_divisor(5538,1105)
greatest_common_divisor(8764,7732)        
