__Experimental__ MSP430 toolchain for the SPARK/Ada language using the Alire package manager.

This index includes the following crates for Linux x86_64. Windows and Mac are not supported.
 - gnat_msp430_elf
 - gprbuild

The updated gprbuild includes a patched gprconfig linker.xml that includes the msp430-elf toolchain. You *must* select `gprbuild 23.0.0` in order to use the `gnat_msp430_elf` toolchain.

```
alr index --add git+https://github.com/JeremyGrosser/alire-index-msp430.git --name msp430
alr toolchain --select
```
