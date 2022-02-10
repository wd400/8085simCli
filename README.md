# 8085simCli
8085 sim CLI version


Clone the repository 


``` 
git clone https://github.com/shrekfanboi/8085simCli
cd 8085simCli
```

Ensure you have python installed and is set in your PATH

execute the execute.py with a text file that you want to execute.

```
python execute.py somefile.txt -options

-reg     display registers in the output
-flag    display flag values in the output
-port    display the ports in the output

-start [MEM] specify a start  memory location for the compiler to start execution from.

-read [MEM]  display a certain memory location after the compiler executes.

-output [FILE] pipe the output to a text file instead of logging in console.

```

You can get the details of these options using

```python
python execute.py -help
```
