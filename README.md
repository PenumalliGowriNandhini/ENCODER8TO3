# ENCODER8TO3
```
module encoder(d,a0,a1,a2);
input[7:0]d;
output a0,a1,a2;
assign a2=d[7]|d[6]|d[5]|d[4];
assign a1=d[7]|d[6]|d[3]|d[2];
assign a0=d[7]|d[5]|d[3]|d[1];
endmodule
```
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/824226c8-c767-44b5-ab35-26fed65b195e)
# Truth Table
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/e228c14b-b814-40c8-92eb-748d48570c04)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/6fa5fe84-fe6f-472d-b9c0-e6dfa17413d3)
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/7d147e2a-ba03-4714-baee-17615c9c50c1)
# output
![encoder](https://github.com/PenumalliGowriNandhini/ENCODER8TO3/assets/163722612/ba5ab12c-9841-4dda-830f-3022481fd477)



