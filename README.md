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
