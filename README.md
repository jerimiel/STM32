The repo contains codes that use hal and sometimes low level registers to program the stm32f446re. 

In UART_blocking_IT_DMA, all three methods of UART implementation have been carried out for uart receive, the blocking function prevents any operation till it has been run, while the interrupt and DMA methods are mostly preferred due to them being non blocking.

