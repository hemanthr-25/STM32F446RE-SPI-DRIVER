STM32F446RE SPI Driver Development
Welcome to the SPI driver development project for the STM32F446RE microcontroller. This project demonstrates low-level driver development for the SPI peripheral without using any HAL libraries, directly accessing STM32 registers.

Features
1) SPI Initialization
2) SPI Transmit and Receive Polling based Operations
3) Interrupt-based TX and RX handling

Sample Projects
There are a few sample projects included in this repository to demonstrate the usage of the SPI driver:
1) 004_SPI_sendDATA.c: Demonstrates basic SPI send API.
2) 005_Spi_arduino.c : Demonstrates basic SPI send API using stm32(MASTER)<->Uno(SLAVE)
3) spi_ardunio_rx.c : Demonstrates basic SPI recieve API using stm32(MASTER)<->Uno(SLAVE)
4) SPI_interrupt_test : Demonstrates basic SPI send and recieve API (Interrupt based) using stm32(MASTER)<->Uno(SLAVE)

🎥 Project Demo
Watch the project demo on YouTube:
Watch the video
1) [Watch PART-1]( https://youtu.be/DMhUvqvt3S8)
2) [Watch PART-2]( https://youtu.be/DNYoDrNcQ2Y)
3) [Watch PART-3]( https://youtu.be/u9P1s23S0rY)
