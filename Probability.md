
Probability for Machine Learning

ML is about making predictions in uncertain situations, and probability is the math of uncertainty.

⸻

Why Probability Is Important in ML?
Machine Learning works with uncertain, noisy, and incomplete data.
Probability provides a way to measure uncertainty and make informed decisions.


Basic Probability Formula
￼


Complement Rule

Probability of NOT happening:

Formula
￼
Used in classification models.



Independent Events

Two events are independent if one does NOT affect the other.

Example:

Coin A: P(H) = 0.5
Coin B: P(H) = 0.5

Combined:
P(A and  B) = 0.5 × 0.5 = 0.25

ML Example: Used in Naive Bayes classifier


Conditional Probability

Probability of A given B:
￼
Example:

Dice = {1,2,3,4,5,6}
Odd numbers = {1,3,5}
Greater than 2 = {3,5}

Then, P = 2/3

⸻

Bayes’ Theorem (Very Important for ML)

Used to answer:
If something happened, what is the real cause?

Formula:
￼
Got it — you want a tight, precise, gap-free version that fits cleanly into your doc. Here it is:

⸻

Example

Suppose a college has students from : CS = 100, Bio = 50, Total = 150
Black hoodie wearers (BH) : CS = 30, Bio = 5, Total = 35

To find: Probability that a student is from CS given they wear a black hoodie.

First calculate:

P(CS) = 100 / 150 = 0.67
P(BH | CS) = 30 / 100 = 0.3
P(BH) = 35 / 150 = 0.233

Bayes’ Theorem:

P(CS | BH) = (P(BH | CS) × P(CS)) / P(BH)

Substitute values:

= (0.3 × 0.67) / 0.233
= 0.86

Final Result: There is an 86% chance that a student wearing a black hoodie belongs to the CS department.

ML Example: Used in Naive Bayes classifier -  Spam detection, Medical diagnosis




Probability Distribution

Tells how values are spread and how likely each value is.

Used in ML to:
• Understand data behavior
• Make predictions
• Calculate loss
• Detect anomalies


Types of Distributions

Discrete Distribution

Used when values are countable and separate (like Yes/No, 0/1).

Examples:
• Bernoulli – Single trial with two outcomes (success/failure).
• Binomial – Multiple trials counting number of successes.

Used in ML for binary classification (spam / not spam).

Continuous Distribution

Used when values can take any value within a range (like height or weight).

Examples:
• Normal Distribution – Bell-shaped curve, most common in real data.
• Uniform Distribution – All values have equal probability.

Used in ML to model real-world measurements and prediction errors.

Without probability, Machine Learning cannot reason.
