# Naive + Welzl Algorithm for the smallest circle problem

`Amine Benslimane`  

`amine.benslimane@etu.sorbonne-universite.fr`

`Master 1 STL - Sorbonne Université`

`Jan 2021`


We present both naive and Welzl Algorithm to compute the smallest circle of a set of input points in 2D.

## Naive Algorithm

A naive way to compute the smallest circle is to test all combinations of points and verify for each combination if it's englobing all the points, choose the smallest one. 

It's time complexity is O(n⁴). 
See the details on our paper. 

## Welzl Algorithm

The Welzl Algorithm is a fast Algorithm presented by Emo Welzl in 1991 and is described in the following paper : 

[Emo Welzl, "Smallest enclosing disks (balls and ellipsoids). In : New Results and New Trends in Computer Science. Under direction of Hermann MAURER. Berlin, Heidelberg : Springer Berlin Heidelberg, 1991, p 359-370 ISBN : 978-3-540-46457-0](www.stsci.edu/~RAB/Backup%20Oct%2022%202011/f_3_CalculationForWFIRSTML/Bob1.pdf)

We used the VAROUMAS benchmark for testing our algorithm, (1664 instances of test, 256 points for an instance of test) see the benchmark on : [Varoumas Benchmark](www-apr.lip6.fr/~buixuan/files/algav2020/Varoumas_benchmark.zip)

Its time complexity is : O(n) (linear), see the demonstration on Welzl's paper.

## How to use

- On `public Circle calculCercleMin(ArrayList<Point> points`, decomment the choosen algorithm (naive or welzl)

- Select `run` on `target` in `build.xml` run configuration, enjoy :)

## Output example

We get the following results for a Varoumas instance of 256 points (Naive vs Welzl) : 

![naivwelzl](https://user-images.githubusercontent.com/77028316/122648758-dc501700-d12a-11eb-9447-37f8a187a784.png)

## Results Naive vs Welzl
We clearly see that the Welzl Algorithm is much efficient

![temp](https://user-images.githubusercontent.com/77028316/122648926-98114680-d12b-11eb-9a1a-9c2b31958eb5.PNG)


## Licence
GPL v3, feel free to use this code.
