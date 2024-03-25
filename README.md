# FULL_ADDER
# Truth Table
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/02ead8f5-d958-4c89-ac51-368ca086cf41)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/418e00aa-ed19-4ab3-a413-bae9575bff0e)
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/0c26fe47-d78c-43dd-ac0d-804e427a3bbc)
# Program
```
module full_adder_s (
    input a,b,cin,
    output sum,carry);

wire w1,w2,w3,w4;     

xor(w1,a,b);
xor(sum,w1,cin);       
and(w2,a,b);
and(w3,b,cin);
and(w4,cin,a);
or(carry,w2,w3,w4);     

endmodule
```
# Output
![Screenshot 2024-03-25 134849](https://github.com/Vijayananthperumal22/FULL_ADDER/assets/107705127/4d293f9e-23a7-4cf5-a426-596ddaf481e5)

