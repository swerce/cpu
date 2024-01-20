```plaintext
   Vcc
    |
    |
   Rpu
    |
    |
   +----+       +--- NMOS (Qn_A) -- IF Output
   |    |       |
   |    +---+   +--- NMOS (Qn_B)
   |        |   |
   |        +---+
   |        |
   +----+   |   +--- PMOS (Qp_A) --+
   |    |   |   |                   |
   |    +---+   +--- PMOS (Qp_B)    +--- IF Output
   |    |       |                   |
   +----+       |                   |
   |            +-------------------+
   |    
   |            +--- NMOS (Qn_A) -- ELSE Output
   |            |
   +----+       +--- NMOS (Qn_B)
   |    |       |
   |    +---+   +--- NMOS (Qn_C)
   |        |   |
   |        +---+
   |        |
   +----+   |   +--- PMOS (Qp_A) --+
   |    |   |   |                   |
   |    +---+   +--- PMOS (Qp_B)    +--- ELSE Output
   |    |       |                   |
   +----+       |                   |
                +-------------------+
    
    Rpd
    |
    |
   Inv
    |
   GND
```

In this visual representation:

    Vcc is the power supply, and GND is the ground.
    Rpu is the pull-up resistor, and Rpd is the pull-down resistor.
    Qn_A, Qn_B, Qn_C are NMOS transistors forming the AND gates.
    Qp_A, Qp_B are PMOS transistors forming the OR gates.
    Inv is the inverter.
    Different paths represent different logic conditions and their corresponding output paths (IF Output, ELSE Output, and Result).
