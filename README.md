## Bounded ACh Unification 


We designed an algorithm that consisting of inference rules to solve an unification problem modulo the theory of homomorphism over an Associativity-Commutativity operator.

This work has been presented at the international workshop on unification [UNIF18](http://unif2018.cic.unb.br) organized at Oxford University, UK. The paper (two versions) is presented below.

* Ajay Kumar Eeralla, Christopher Lynch. [Bounded ACh Unification](http://unif2018.cic.unb.br/BookletUNIF2018.pdf) (32nd International Workshop on Unification (UNIF 2018), Informal Proceedings, Oxford, 7th July, 2018).

* Ajay Kumar Eeralla, Christopher Lynch. [Bounded ACh Unification](https://arxiv.org/abs/1811.05602) (extended version of the paper).


## Prerequisites 
To run the algorithm you will need to have installed Maude, a high performance reflective language. 

### Install ###
Download and install Maude from [here](http://maude.cs.illinois.edu/w/index.php?title=The_Maude_System).

### Instructions to run the program ###
Download .maude file(s) to a directory. Then navigate to the directory and use the following commands:
* Load the file using following command
```
> Load filename.maude
```
* To test the program
```
> red in Unif : SolEqsACH (p , b )
```
where `p` is an unification problem and `b` is a bound under which we are looking for soluctions

## Authors 

* **Ajay Kumar Eeralla** (ajay.eeralla@gmail.com/ae266@mail.missouri.edu)
* **Christopher Lynch** (clynch@clarkson.edu)
