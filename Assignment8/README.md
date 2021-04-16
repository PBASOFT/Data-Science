# Assignment 8 - Classification

## Task 1: – Bayes’ theorem

Formula: <img src="https://latex.codecogs.com/gif.latex?\inline&space;P(A|B)=\frac{P(B|A)P(A)}{P(B)}" title="P(A|B)=\frac{P(B|A)P(A)}{P(B)}" />


1.  **60% of the kids play football, and 36% of the kids play ice hockey. 40% of the kids who play football also play ice hockey. What percent of those that play ice hockey also play football?**

24% of those that play ice hockey also play football:

<img src="https://latex.codecogs.com/gif.latex?\frac{0,4\cdot&space;0,36}{0,6}&space;=&space;0,24" title="\frac{0,4\cdot 0,36}{0,6} = 0,24" />


2. **40% of the kids like music, and 24% of the kids like to dance. Given that 30% of those that like
music also likes to dance, what percent of those that like to dance also likes music?**

32% of those that like to dance also likes music:

<img src="https://latex.codecogs.com/gif.latex?\frac{0,4\cdot&space;0,24}{0,3}=0,32" title="\frac{0,4\cdot 0,24}{0,3}=0,32" />


3. **In a factory, machine X produces 60% of the daily output and machine Y produces 40% of the daily
output.
2% of machine X’s output is defective, and 1.5% of machine Y’s output is defective.
One day, an item is inspected at random, and found to be defective. What is the probability that it
was produced by machine X?**

What we want to achieve:

<img src="https://latex.codecogs.com/gif.latex?P(X|defect)&space;=&space;\frac{P(defect|X\cdot&space;P(X))}{P(defect)}" title="P(X|defect) = \frac{P(defect|X\cdot P(X))}{P(defect)}" />

We know that P(defect|X) = 0,02 and P(X) = 0,6

We then have to find P(defect):

<img src="https://latex.codecogs.com/gif.latex?\inline&space;P(defect)&space;=&space;0,6\cdot&space;0,02&space;&plus;&space;0,4&space;\cdot&space;0,015&space;=&space;0,018" title="P(defect) = 0,6\cdot 0,02 + 0,4 \cdot 0,015 = 0,018" />

We can now do the theorem:

<img src="https://latex.codecogs.com/gif.latex?\inline&space;\frac{0,02\cdot&space;0,6}{0,018}&space;=&space;0,66" title="\frac{0,02\cdot 0,6}{0,018} = 0,66" />

And state that there is a 66% probability that a defect was produced by machine X
