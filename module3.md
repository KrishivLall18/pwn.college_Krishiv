# Pondering Paths

## The Root
To invoke a program by using its path

### Solve
**Flag:** `pwn.college{8kAcTyHyQVQDz15i2oMUNE6xxgj.QX4cTO0wSM4EzNzEzW}`

Typing the absolute path followed by the program pwn

```bash
/pwn
pwn.college{8kAcTyHyQVQDz15i2oMUNE6xxgj.QX4cTO0wSM4EzNzEzW}
```

### New Learnings
The use of Absolute Path

### References 
Linux Librarium 2 - The File System

## Program and Absolute Paths
To explore the challenge directory

### Solve
**Flag:** `pwn.college{gI8dZgwNmultbDXZNpPvq3EC6vc.QX1QTN0wSM4EzNzEzW}`

Typing in the challenge directory and accessing program run inside it

```bash
/challenge/run
pwn.college{gI8dZgwNmultbDXZNpPvq3EC6vc.QX1QTN0wSM4EzNzEzW}
```

### New Learnings
The use directories

### References 
Linux Librarium 2 - The File System

## Position thy self
To change and access a new directory

### Solve
**Flag:** `pwn.college{8p4WcZ8C5vRKlOGWSOYFfvD67Cu.QX2QTN0wSM4EzNzEzW}`

using cd to access tmp directory and run /challenge/run

```bash
cd /tmp
/challenge/run
pwn.college{8p4WcZ8C5vRKlOGWSOYFfvD67Cu.QX2QTN0wSM4EzNzEzW}
```

### New Learnings
How to change and access new directories 

### References 
Linux Librarium 2 - The File System

## Position elsewhere
To change and access a new directory

### Solve
**Flag:** `pwn.college{AZb5MdP6pviSHnIelTn0pYq7eQ5.QX3QTN0wSM4EzNzEzW}`

using cd to access tmp directory and run /challenge/run

```bash
cd /use/bin
/challenge/run
pwn.college{AZb5MdP6pviSHnIelTn0pYq7eQ5.QX3QTN0wSM4EzNzEzW}
```

### New Learnings
How to change and access new directories 

### References 
Linux Librarium 2 - The File System

## Position yet somewhere elsewhere
To change and access a new directory

### Solve
**Flag:** `pwn.college{8ehdALGOGALzwb1myouo9G2edxO.QX4QTN0wSM4EzNzEzW}`

using cd to access tmp directory and run /challenge/run

```bash
cd /etc/apt/sources.list.d
/challenge/run
pwn.college{8ehdALGOGALzwb1myouo9G2edxO.QX4QTN0wSM4EzNzEzW}
```

### New Learnings
How to change and access new directories 

### References 
Linux Librarium 2 - The File System

## Implicit relative paths, from /
To use a relative path to access directories

### Solve
**Flag:** `pwn.college{MuT-vTI_GqO4cfI3_kYZN7oLrN3.QX5QTN0wSM4EzNzEzW}`

using cd to cwd we then access the relative path to it which is challenge/run

```bash
cd /
challenge/run
pwn.college{MuT-vTI_GqO4cfI3_kYZN7oLrN3.QX5QTN0wSM4EzNzEzW}
```

### New Learnings
How to change and access relative directories 

### References 
Linux Librarium 2 - The File System

## Explicit relative paths, from /
To use a relative path to access directories

### Solve
**Flag:** `pwn.college{A_EBYXi_k6FTtj3RDZLnSRjt61k.QXwUTN0wSM4EzNzEzW}`

using cd to cwd we then access the relative path to it which is challenge/run

```bash
cd /
./challenge/run
pwn.college{A_EBYXi_k6FTtj3RDZLnSRjt61k.QXwUTN0wSM4EzNzEzW}
```

### New Learnings
How to change and access relative directories 

### References 
Linux Librarium 2 - The File System

## Implicit relative paths
To use a relative path to access directories

### Solve
**Flag:** `pwn.college{g3o_cQPA-0fe1ivKVMqqGYj_ze_.QXxUTN0wSM4EzNzEzW}`

using cd to cwd we then access the relative path to it which is challenge/run

```bash
cd /challenge
./run
pwn.college{g3o_cQPA-0fe1ivKVMqqGYj_ze_.QXxUTN0wSM4EzNzEzW}
```

### New Learnings
How to change and access relative directories 

### References 
Linux Librarium 2 - The File System

## Home sweet Home
To use home directory to copy the flag into another file

### Solve
**Flag:** `pwn.college{sSSVXnMXH5dK55ZZ4ELa3BTTlkl.QXzMDO0wSM4EzNzEzW}`

using ~/ to acess files in home built directory

```bash
echo ~/x
/challenge/run ~/x
pwn.college{sSSVXnMXH5dK55ZZ4ELa3BTTlkl.QXzMDO0wSM4EzNzEzW}
```

### New Learnings
How to  access home directory 

### References 
Linux Librarium 2 - The File System

