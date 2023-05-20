# AIM:
Design and simulate the logic diagram using Verilog.    
                      F=(X+Y')(X'+Y)Z'
 
 


# THEORY

# LOGIC DIAGRAM:


# NETLIST DIAGRAM:
![assignment1(de)logic](https://github.com/shoaib3136/Simulation-project--Digital-Electronics/assets/117919362/46f58906-fddf-431b-b558-e9ef2a7d643d)



# TIMING DIAGRAM:
![assignment1(de)](https://github.com/shoaib3136/Simulation-project--Digital-Electronics/assets/117919362/f5c3e161-e811-4e4a-9ed8-7bbdb624d2d2)


# PROGRAM:
```
Name:Shaik Shoaib Nawaz
Reg No:212222240094
module assignment1 (x,y,z,f);
input x,y,z;
output f;
wire a,b,c,d,e;
not (a,x);
not (b,y);
not (c,z);
and (d,a,b,c);
and (e,x,y,c);
endmodule
```
# REFERENCE
