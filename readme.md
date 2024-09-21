Here is to learn the CAN communication protocol for the industrial devices. 

## TODO

- [x] use the stm32cubemx to creat the CAN communication project
  - [x] transmit the data
  - [x] receive the data
- [x] add the display module to show the CAN data
- [ ] add the sensor module to read the data
- [ ] encrypt the data then send it to the CAN bus

## download

after build the project by the cmake. you can use the openocd to download the program to the stm32f103c8t6 chip.

```shell
openocd -f openocd.cfg -c "program build/Release/stm32f103c8t6_can_hal_test.elf verify reset exit"
```