# hw3-1
Specification: SPI spi(D11, D12, D13); DigitalOut cs(D9); SPISlave device(PD_4, PD_3, PD_1, PD_0);

Lab set up: connect the board as program 3_2 from lab7 to acheive spi loopback

expected result: After the slave receive the mode and value it will operate with the value then send the new value back to master and print it out
