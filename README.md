# Multiplexer4to1
# Truth Tabel
![image](https://github.com/RESMIRNAIR/Multiplexer4to1/assets/154305926/f1dac9e1-e938-4072-bfa9-c17a0a54b7c7)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/Multiplexer4to1/assets/154305926/f8ea8610-f6fc-4de3-a68a-5a9a4cfcd673)
# program
```
module mux(a,b,c,d,s0,s1,y);
input a,b,c,d,s0,s1;
output y;
assign y=s1 ?(s0?d:c):(s0?b:a);
endmodule
```
# OUTPUT
![WhatsApp Image 2024-04-01 at 13 14 53_63d8231e](https://github.com/dhivakaran09/Multiplexer4to1/assets/164842673/756b0dcf-db59-4ccb-9c00-d1f355ae740a)
```
