# Facility Location
An example of using Gurobi to solve a facility location problem

![](screenshot.png?raw=true)

# Running the example

1. Start Python's webserver from the command line
    ```
    make
    ```

2. Point your browser at http://localhost:8000

3. Add some clients by clicking your mouse in the demo area.

4. Click "Compute" to locate the facilities.

# Performing an optimization

To just solve the model (without running a web server) do:

```
make test
```

