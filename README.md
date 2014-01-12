# NRF24L01+ Library

### Kevin Cuzner

## Overview

This library is designed to be a relatively platform agnostic implementation of
a protocol for communicating with the NRF24L01 chip.

## Objectives

 * Compile for both raspberry pi and AVR
 * AVR uses built in SPI module or bitbanging
 * Raspberry Pi uses linux spidev stuff
