# Week 2

*As always: make a copy (fork) of this repository to commit changes to*

[slides](https://docs.google.com/presentation/d/1-Mbez8TbJL6tEYH15HQMPqfbiUqQAintPIqHmLVMj9A/edit#slide=id.g4ca55399dd_0_0)

## Week 1 Review

### Git/Github continued
- Forking
- Pull requests (turning in assignments)

## Javascript Fundamentals
- Data types
- Conditions
- Functions
- Scope

## Assignment

#### Code Academy

* Complete Units 5-8 in the [Javascript coursework](https://www.codecademy.com/learn/introduction-to-javascript)
  - Arrays
  - Loops
  - Iterators (loopy functions)
  - Objects and properties

### Project

We're producing a simple map to help people find health centers in the
Philadelphia area. Our application has two goals:

First, we'd like to provide this data in javascript arrays. We should
print these arrays to the console.
* On application start, use `console.log` to show an array of arrays
  in which the first sub-array contains keys and the rest of the arrays
  contain the 'rows' of our data
* An example of what this would look like for a different dataset:
  `[["name", "job"],["Bruce Springsteen", "Musician"],["Terry Gross", "Journalist"]]`

Second, we want to know where the health centers are located within the
zip codes from 19140 to 19149 (inclusive).
* All and only markers found within the zip code range from 19140 to
  19149 should appear
* Each marker should have a popup when clicked which tells us the location name

#### Extra

Some health centers offer dental services as well. Can you find a way to
give centers that provide dental services a different icon than those
that do not?
