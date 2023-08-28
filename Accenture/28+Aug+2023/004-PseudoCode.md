## Pseudo Codes
<pre>Integer p, q, r
set p=3, q=5, r=4
r=(5^2)+p
for(each r from 3 to 5)
	q = (p+9)&r
	p = 3&p
	q = (r^q)+r
	p = (5+8)&p
End for
Print p+q

# Options
9
11
57
37
</pre>

## Must know before solving
XOR Operator Truth Table(^):
| A | B | A XOR B |
|---|---|---------|
| 0 | 0 |   0     |
| 0 | 1 |   1     |
| 1 | 0 |   1     |
| 1 | 1 |   0     |

AND Operator Truth Table(&):
| A | B | A AND B |
|---|---|---------|
| 0 | 0 |   0     |
| 0 | 1 |   0     |
| 1 | 0 |   0     |
| 1 | 1 |   1     |


## Explaination
![1](000-resc/91771a99-1dc5-4e56-9d78-a70f0366c131.jpg)
![2](000-resc/7ca2ca58-37aa-41c9-8210-8e825cc4cb1d.jpg)
![3](000-resc/1aac6112-76dc-4ec0-8b54-3649a548c1be.jpg)
![4](000-resc/3263bd84-d209-49c4-9b73-890c447dbc70.jpg)


