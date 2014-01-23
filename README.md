Chemistry-Compound-Calculator
=============================

> Calculates the formula of the compound given the percentage of C, H, N, and O.

I created this for Chemistry 11, to quickly calculate the answers to an assignment.
After coding this, I remembered the formula and did not need to use the script, again ;).

-----

## Usage

Open the `Compound Formula Solver.scpt` with the [Mac AppleScript Editor](http://en.wikipedia.org/wiki/AppleScript_Editor).

## Example Usage

### Input

```
C=1, H=1, N=1, O=1
```

### Output

```
In a 100 g sample:
1%C  --> 1g x [1 mol / 12.01]    ==> 0.08 mol
1%H  --> 1g x [1 mol / 1.01]     ==> 0.99 mol
1%N  --> 1g x [1 mol / 14.01]    ==> 0.07 mol
1%O  --> 1g x [1 mol / 16.0]     ==> 0.06 mol
Divide by Lowest: ( ÷0.06)
C   0.08/0.06 ==> 1.33
H   0.99/0.06 ==> 16.5
N   0.07/0.06 ==> 1.17
O   0.06/0.06 ==> 1.0
Formula of Compound:
C1.33 H16.5 N1.17 O1.0
```
