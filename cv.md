# Kurmaz Aliaksander
----
## Junior Frontend Developer
====
## Contact information:
**Phone:** +375 447813882
**E-mail:** 375 447813882@gmail.com
## Briefly About Myself:
I work in the civil service. I want to improve my professional skills in the field of programming for the purpose of self-development and improving my qualifications.
****
## Skills and Proficiency:
* English language
* working with customs legislation
* customs control
## Code example:
> Peak array index KATA from CODEWARS: Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.

function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
## experience
* merchandising - Bobruisk shopping center
* customs inspector - Mogilev customs
## Education
Mogilev State University of Food commodity expert-expert
accountant-economist

## English 
A2
