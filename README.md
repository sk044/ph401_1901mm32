# PH401 : Introduction to Nanomaterials

## Group Members
------------------------------------
| Name                  | Roll No. |
|-----------------------|----------|
| Shubham Kumar         | 1901MM32 |
------------------------------------

## Question 1

```
Write a computer program to deduce the total number of atoms and surface atoms for different shell of cuboctahedral/spherical shape. Plot % of atoms in bulk/surface versus particle size. The user should get idea to generate the thickness or size of nanoparticle for a particular application (optical/electrical/magnetic/strength)
```

### Usage

```
Run index.html 
```

## Implementation

### Inputs
```
1. Shape (Cuboctahedral/Spherical)
2. Application (Optical/Electrical/Magnetic/Strength/None)
3. Range of size of nanoparticle (default: 1-50 nm)
```

### Output
```
Graph of % of atoms in Bulk/Surface vs. Particle Size for the chosen Shape and Application
```

### Formulas Used
```
Total Number of atoms in Cuboctahedral shape = (10k^3 + 15k^2 + 11k + 3)/3

Number of atoms on the surface of Cuboctahedral shape = (10k^2 + 2)

Total Number of atoms in Spherical shape = (10k^3 - 15k^2 + 11k - 3)/3

Number of atoms on the surface of Spherical shape = (10k^2 - 20k + 12)

where, *k* is the size of the atom
```

