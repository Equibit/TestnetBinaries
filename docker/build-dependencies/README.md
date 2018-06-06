### Building equibitd dependencies with Docker

Launch the build script to compile the libraries
```
./build
```

Once the script is completed, you should find a folder called `eqb` has been created.
Copy the `equibitd` file to the current folder so that you have, it the same level:
```
eqb/
equibitd
run
```

Check to see if everything runs correctly:
```
./run --help
```

Start the `run` script with your command-line parameters to execute `equibitd` with the compiled libraries.
```
./run command-line-parameters
```
