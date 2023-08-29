<pre>
Integer a, b,c
Set b = 10
for(each a from 1 to 4)
   b = b+a
end for
c=b/5
Print c

a. 5
b. 4
c. 10
D. NOTA
</pre>

## Solution
b = 10
<pre>
for(a=1;a<=4;a++){
    Loop starts
    when a = 1
        b = b + a = 10 + 1 = 11      --{b value is updated form 10 to 11}
    when a = 2
        b = b + a = 11 + 2 = 13      --{b value is updated form 11 to 13}
    when a = 3
        b = b + a = 13 + 3 = 16      --{b value is updated form 13 to 16}    
    when a = 4
        b = b + a = 16 + 4 = 20      --{b value is updated form 16 to 20}
    
}
</pre>

when program ends<br>
c = b /5 --[given]<br>
last b value was 20 <br>
so 20/5 = 4
## Option (B)
