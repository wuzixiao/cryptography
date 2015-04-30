#Crypto on-line course

## Introduction
====

Where use:

* HTTPs
* wifi
* encryption file
* manymany

sym.encrtption:
two parts use the same key!

E.D: cipher 

Single use key:

* encrptied email

Multi use key:

* encrpted files
* need more machinery than for one-time key


##What is cryptography

basically about secure communication

more :

* Digital signatures
* Anonymous communication
* digital cash
* Elections

Three steps in cryptography:

* Precisely specify threat model
* propose a construction
* prove that breaking construction under thread mode will solve an underlying hard problem


## History of cryptography

#### subsitution cipher

How to break a subsitution cipher

1 Use frequency of english letters

"e" 12.7%
"t" 9.1%

2 Use frequecey of paris of letters 

#### Vigener cipher

k = C R Y P T O

k + m = c

Still use the frequency of enlish letters, if we get a large amount of letters we will try to guess the k

#### Roter Machines

Early exmaple : the Hebern machine

famous: the Enigma(3-5 rotors)

#### Data Encryption Statndard

DES: #keys=2**56 , its block size is 64bits, not enough for today, people hackers can use brute force method to break it.

Today: AES(2001) Salsa20(2008)
They are 128bits, not easy to break for now.

### Discrete probability(Crash cource)

U: finite set
P over U is a function P: U-->[0,1]


1. Uniform discribution: for x belongs to U: P(x) = 1/U
2. point discribution:

**Event**: it is a subset of U

**Independence Event** Pr[A and B] = Pr[A]*Pr[B] if event A and B are independence

U = {0,1}2 = {00,01,10,11} 

**XOR** you are also important here!!
Because Y a rand. var. over {0,1}n, X anindep.uniform var on {0,1}
Then Z:=Y XOR X is also an indep. uniform!!!


**Birthday paradox** Let r1,..rn in U, they are indep. indentically distributed random vars.

when n = 1.2 * squre(|U|) then Pr[if i!=j: ri = rj] >= 1/2

1.2 * squre(365) = 24 .

24 person in a room, the propability of two of them have the same birthday larger than 0.5



