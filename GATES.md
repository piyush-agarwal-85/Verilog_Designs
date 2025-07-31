# XOR Gate using Dataflow modeling
```verilog
`timescale 1ns / 1ps

module XORgate(
    input a,b,
    output y
    );
    assign y = a ^ b; 
endmodule
```

# truthtable

| Inputs |   | Outputs |
|--------|---|---------|
| A      | B | C       |
| 0      | 0 | 0       |
| 0      | 1 | 1       |
| 1      | 0 | 1       |
| 1      | 1 | 0       |


## Schematics
![Alt Text](https://github.com/piyush-agarwal-85/Verilog_Designs/blob/main/SchematicsGATES.png)

## Simulation
![Alt Text](https://github.com/piyush-agarwal-85/Verilog_Designs/blob/main/SimulationGATES.png)
