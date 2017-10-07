# STP-1

## General information
For the delivery of laboratory work you need to have:
  - a report that includes the source code of your laboratory work;
  - commited source code on your repository of github (each laboratory work, that student do, should be committed to his repository with the message like: "done lab 1");
  - you also need to answer all the questions that will be asked. 

Questions for laboratory work are given below, but they are approximate. During the delivery of the laboratory work, everything that you did in it  will be asked and all the details of your code will be disassembled.

## Contents
- [Lab 1](#lab-1)
  - [Task](#lab-1-task)
  - [Questions](#lab-1-questions)
- [Lab 2](#lab-2)
  - [Task](#lab-2-task)
  - [Questions](#lab-2-questions)
- [Lab 3](#lab-3)
  - [Task](#lab-3-task)
  - [Questions](#lab-3-questions)
- [Lab 4](#lab-4)
  - [Task](#lab-4-task)
  - [Questions](#lab-4-questions)
  
#### Lab 1
##### Lab 1 task
1) Create a repository on the github.com. If the repository is private, the student should 'invite' me to his repository
2) Install JAVA
3) Install [IntelliJ IDEA](https://www.jetbrains.com/idea/). **Keep in mind** - you can get [lincense](https://www.jetbrains.com/student/) for free.
4) Install Gradle
5) Create project with gradle
6) Print in console `Hello World`

##### Lab 1 questions
- What is this JAVA? Their pluses, minuses
- What is JDK/SDK/JRE?
- How to run java program by console, using build tools?
- What is `*.jar`/`*.war` files?
- What is the Gradle/Maven/Ant? Why should we use builds tools? Gradle's tasks
- What is github? How create and push commit to repository?
- What is artefact/group id?

#### Lab 2
##### Lab 2 task
1) Write a program that asks the user the number of array elements, then in
loop the user enter values for each item.

variant | task
:------------------------:|:------
1 | Find the number of positive items; <br/> Find the sum of the elements that are larger than 3; <br/> Find the maximum element of the array; <br/> Find the number of negative elements; <br/> Find the sum of negative elements; <br/> Find the minimum element that is multiple 5;
2 | Find the number of paired items; <br/> Find the sum of the elements multiplied by 3; <br/> Find the difference between the maximum and the minimum elements array; <br/> Find the arithmetic mean of the array; <br/> Find the sum of the largest and smallest elements of the array; <br/> Find the maximum by module element of the array
3 | Find the arithmetic mean of the paired array elements;<br/> Find the sum of the minimum positive element of the array and his numbers;<br/> Find the product of the most negative and the smallest paired elements of the array; <br/> Find the number of items that are multiple 5; <br/> Find the sum of the paired elements of the array standing on odd places; <br/> Find the sum of the second and most positive elements array
4 | Find the geometric mean of paired array elements; <br/> Find the largest number by module of the array element; <br/> Find the maximum paired item in the array; <br/> Determine the arithmetic mean of the minimum elements of the array; <br/> Find the module-minimized array element; <br/> Find the sum of items in the interval [0; 10]
5 | Determine the mean geometric numbers of the maximum and minimum elements of the array; <br/> Find the difference between positive and negative integers of an array; <br/> Find the number of positive elements of the array; <br/> Find the sum of negative items; <br/> Find the sum of array elements in which the index is multiple 3; <br/> Find the product of the largest and smallest elements of the array
2) Output parameters such as the array dimension are entered from the keyboard, the contents of the array generate with `Random#nextInt`. After the user inputs the dimension to generate the matrix, and output take it to the screen, then complete the task and display the result.

variant | task
:------------------------:|:------
1 | Given an integer square matrix of order 8. Find the least of the values of the column items that have the largest amount of modules elements of If there are several columns, then take the first one.; <br/> The given positive integer n is an integer square matrix of order `n` Obtain `bi, ..., bn`, where `bi` is: a) the least of the values of the elements that are at the beginning of the `i`-th matrix line to the element belonging to the main diagonal including; b) the value of the first in the order of the positive element of the `i`-th line (if there are no such elements, then take `bi = l`).
2 | The given positive integer `n` is an integer square matrix of order `n`. Get `bi, ..., bn`, where `bi` is: a) the sum of the elements located behind the first negative element in `i`-th line (if all elements of the line are non-negative, take `bi = 100`); b) the sum of the elements preceding the last negative element `i`-th line (if all elements of the line are non-negative, then take `bi = -l`).; <br/> An integer matrix of order `n` is given. Find line numbers: a) all elements of which are zeros; b) the elements in each of them are the same.
3 | An integer matrix of order `n` is given. Find line numbers: a) all elements of which are even; b) the elements of each of them form a monotonous sequence (monotonically decreasing or monotonically increasing).; <br/> This is a valid square matrix of order 10. In lines with negative element on the main diagonal find: a) the sum of all elements; b) the largest of all elements.
4 | This is a valid square matrix of order `n`. Consider those elements which are located in rows starting with a negative element.; <br/> Find the sum of those that are located respectively below, above and on main diagonal; <br/> This is a valid square matrix of order 9. Obtain an integer square matrix of the same order in which the element is equal to one, if the corresponding element of the output matrix is greater than an element, located in its line on the main diagonal, otherwise is zero
5 | This is a valid square matrix of order `n`. Get meaning `x1*xn + x2*x(n-1) + ... + xk*x1`; where `xk` is the largest value of `k`-th elements line of this matrix. ; <br/> The given positive integer `n>2` is a real square matrix of order `n`. Construct a sequence `bi, ..., bn` from zeros and units, in which `bi = 1` then and only then count

##### Lab 2 questions
Possible theoretical questions (questions will not be limited to this list):
- How to find out the size of the array
- How to find out the size of a multidimensional array
- How to display the contents of the array on the screen
- What is an array?
- Based on which two-dimensional arrays are constructed
- What is a pseudo-random number generator.

#### Lab 3
##### Lab 3 task
 - Create an array of numbers that consists of 150 elements. The contents of the array generate with Random#nextInt. 
 - Implement five types of data sorts.
 - Use two libraries to sort the data.
 - Three times perform each of the sorts, including sorts with libraries, with the working time measurement of each of them. 
 - Gather the performance (resources and time) metrics of your sorting and libraries sorting.
 - The time for working of the each sort is output to the console.

**Keep in mind:** Generate an array once, and all sorting algorithms, including libraries for sorting, should use this array. 

variant | task
:------------------------:|:------
1 | bubble sort, insertion sort, quick sort, cycle sort, merge sort;
2 | bubble sort, selection sort, quick sort, odd-even sort, merge sort;
3 | bubble sort, comb sort, quick sort, shell sort, heap sort;
4 | bubble sort, cocktail sort, quick sort, cycle sort, odd-even sort;
5 | bubble sort, insertion sort, quick sort, selection sort, merge sort;
6 | bubble sort, heap sort, quick sort, shell sort, selection sort;
7 | bubble sort, insertion sort, quick sort, cycle sort, shell sort;
8 | bubble sort, heap sort, quick sort, comb sort, cocktail sort;
9 | bubble sort, odd-even sort, quick sort, cycle sort, comb sort;
10| bubble sort, insertion sort, quick sort, heap sort, selection sort.

##### Lab 3 questions
- What is java types? Name all of them.  What is primitive data types? What is  reference data types? What is difference between all of them?
- What is java operators? On which groups all java operators can be divided?  Know the difference and their use cases.
- What is java keywords? Know most of them and the difference and their use cases.
- Know the difference between used sorts. Select the most effective sorting by time and by resources. 
- Depending on the amount of sorting data, will anything change?
- What is :
```groovy 
public static void Main(String[] args){
...
}
```

#### Lab 4
##### Lab 4 task
1) assemble your previous labs in one project
2) fix bugs (static methods and other)
3) refactor your code (each sort method in another class, which implement your interface sort and other best practice with OOP)
4) cover all your code by unit test, code coverage should be more then 80%.
5) connect CI for your test [travis-ci.org](https://travis-ci.org)
6) CI should run your junit test for java 6, java 7, java 8. 
7) add widgets for each CI in your readme
8) add [codecov.io](https://codecov.io) and [codacy.com](https://www.codacy.com)

Advices for steps 4 - 8:
write unit test -> setup travis for making builds from your repository -> connect codecov and codacy -> update your build.gradle -> add widgets to travise, codecov and codacy

##### Lab 4 questions
Questions will be by docs from https://www.dropbox.com/sh/139rfiwlelm1ra3/AABLwvrX2RSi6p935ust08Lxa
