# VLSI-9


4X1MUX 

module mux_4x1(out, i0,i1,i2,i3, s0,s1);  
output out;  
input i0,i1,i2,i3;  
input s0,s1;  
assign out=(~s1&~s0&i0)|(~s1&s0&i1)|(s1&~s0&i2)|(s1&s0&i3);  
endmodule 
