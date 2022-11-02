
# MIPS Processor

## About

In this project, we design a simple MIPS processor in phase one with `SystemVerilog,` After that, we add multicycle memory and cache in phase two, and then in phase three, we add pipelines to the MIPS machine. In phase four, we design a floating-point coprocessor and register file for storing floating-point numbers. <br/>
In the end, we have written a series of tests to check the correct operation of the processor in the test folder, which you can see in the `test` folder.

## Documentation
You can see all doucuments about design and codes in `documemts`.

## Requirement
To run the project, you must have Docker installed on your system.

## Commands
You can use the project by running these commands in the root of the project. <br/>
`make assemble`: assemble all verilog files. <br/>
`make compile`: compile modules. <br/>
`make verify [test name]`: run specific test. <br/>
`make verify-all`: run all tests. <br/>
`make clean`: delete all compiled moudels. <br/>

## Maintainers
- [Iman Mohammadi](https://github.com/Imanm02)
- [Mehdi Alizadeh](https://github.com/alizademhdi)
- [Mohammad Moshtaghi](https://github.com/MohammadMoshtagh)
- [Behzad Nabawi](https://github.com/behzadnabawi)
