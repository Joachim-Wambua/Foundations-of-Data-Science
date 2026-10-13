|     | Foundations |     |     |          | of     | Data      |      | Science |
| --- | ----------- | --- | --- | -------- | ------ | --------- | ---- | ------- |
|     |             |     |     | Question |        | Catalogue |      |         |
|     |             |     |     | Prof.    | Dr.    | Lucie     | Flek |         |
|     |             |     |     | Vahid    | Sadiri | Javadi    |      |         |
|     |             |     |     |          | David  | Kacz´er   |      |         |
1 Question
| Find the | SVD | of the following |     | matrix: |            |     |          |     |
| -------- | --- | ---------------- | --- | ------- | ---------- | --- | -------- | --- |
|          |     |                  |     |         | (cid:20) 3 | 2 2 | (cid:21) |     |
|          |     |                  |     | A       | =          |     | .        |     |
2 3 −2
2 Question
ShowthatforanyA ∈ Rm×n,thematricesATAandAAT possessthesamenonzeroeigenvalues.
3 Question
Given vectors
|           |              |         |      |         |      |          |    |     |
| --------- | ------------ | ------- | ---- | ------- | ------ | --------- | --- | --- |
|           |              |         |      |         | 1      |           | −1  |     |
|           |              |         |      | x =     | 2,   | y = −1, |     |     |
|           |              |         |      |         | 3      |           | 0   |     |
| compute   | the distance | between |      | x and y | using: |           |     |     |
| (a) ⟨x,y⟩ | := xTy;      |         |      |         |        |           |     |     |
|           |              |         |      |  2 1   | 0     |           |     |     |
| (b) ⟨x,y⟩ | := xTAy,     | where   | A := | 1 3    | −1.   |           |     |     |
|           |              |         |      | 0 −1    | 2      |           |     |     |
4 Question
Consider the following bivariate distribution p(x,y) of two discrete random variables X and Y.
|     |     |     | Y\X | x      | x    | x    | x   | x   |
| --- | --- | --- | --- | ------ | ---- | ---- | --- | --- |
|     |     |     |     |        | 1 2  | 3    | 4   | 5   |
|     |     |     |     | y 0.01 | 0.02 | 0.03 | 0.1 | 0.1 |
1
|     |     |     |     | y 0.05 | 0.1 | 0.05 | 0.07 | 0.2 |
| --- | --- | --- | --- | ------ | --- | ---- | ---- | --- |
2
|     |     |     |     | y 0.1 | 0.05 | 0.03 | 0.05 | 0.04 |
| --- | --- | --- | --- | ----- | ---- | ---- | ---- | ---- |
3
Compute:
| (a) The | marginal    | distributions |     | p(x) and | p(y).   |         |     |        |
| ------- | ----------- | ------------- | --- | -------- | ------- | ------- | --- | ------ |
| (b) The | conditional | distributions |     | p(x |    | Y = y ) | and p(y | | X | = x ). |
|         |             |               |     |          | 1       |         |     | 3      |

5 Question
Consider a Gaussian random variable x ∼ N(x | µ ,Σ ), where x ∈ RD. Furthermore, we have
|     |     |     |     |     |     | x   | x   |
| --- | --- | --- | --- | --- | --- | --- | --- |
y = Ax+b+w,
where y ∈ RE, A ∈ RE×D, b ∈ RE, and w ∼ N(w | 0,Q) is independent Gaussian noise.
“Independent” implies that x and w are independent random variables and that Q is diagonal.
| (a) Write | down | the likelihood |     | p(y | | x). |     |     |
| --------- | ---- | -------------- | --- | --- | ----- | --- | --- |
(cid:82)
(b) The distribution p(y) = p(y | x)p(x)dx is Gaussian. Compute the mean µ and the
y
| covariance | Σ   | . Derive |     | your result | in  | detail. |     |
| ---------- | --- | -------- | --- | ----------- | --- | ------- | --- |
y
(c) The random variable y is being transformed according to the measurement mapping
|     |     |     |     |     |     | z = Cy+v, |     |
| --- | --- | --- | --- | --- | --- | --------- | --- |
where z ∈ RF, C ∈ RF×E, and v ∼ N(v | 0,R) is independent Gaussian (measurement)
noise.
| • Write | down |     | p(z | y). |     |     |     |     |
| ------- | ---- | --- | --------- | --- | --- | --- | --- |
•
Compute p(z), i.e. the mean µ and the covariance Σ . Derive your result in detail.
|     |     |     |     |     | z   |     | z   |
| --- | --- | --- | --- | --- | --- | --- | --- |
6 Question
[−1, 1].
Let x and y be independent random variables with uniform distribution in What is the
2 2
| expected | value E(x), |     | E(x2), | E(x−y), | E(xy), | and E((x−y)2)? |     |
| -------- | ----------- | --- | ------ | ------- | ------ | -------------- | --- |
7 Question
Let x be a random variable with probability density 1 for 0 ≤ x ≤ 4 and zero elsewhere.
4
| 1. Use | Markov’s | inequality |     | to bound |     | the probability | that x ≥ 3. |
| ------ | -------- | ---------- | --- | -------- | --- | --------------- | ----------- |
2. Make use of prob(|x| ≥ a) = prob(x2 ≥ a2) to get a tighter bound.
| 3. What | is the | bound | using | prob(|x| | ≥   | a) = prob(xr | ≥ ar)? |
| ------- | ------ | ----- | ----- | -------- | --- | ------------ | ------ |
8 Question
Manually find the best-fit lines (not subspaces that must contain the origin) through the points
in the sets below. Best fit means minimizing the perpendicular distance. Subtract the center
of gravity of the points in the set from each of the points in the set and find the best-fit line for
the resulting points. Does the best-fit line for the original data go through the origin?
| 1. (4,4)   | (6,2) |       |         |     |     |     |     |
| ---------- | ----- | ----- | ------- | --- | --- | --- | --- |
| 2. (4,2)   | (4,4) | (6,2) | (6,4)   |     |     |     |     |
| 3. (3,2.5) | (3,5) | (5,1) | (5,3.5) |     |     |     |     |
2

9 Question
Manuallyfindtheleftandrightsingularvectors,thesingularvalues,andtheSVDdecomposition
| of  | the matrices |     | in the | following | figure: |     |     |     |     |     |
| --- | ------------ | --- | ------ | --------- | ------- | --- | --- | --- | --- | --- |
(1,3)
(0,3)
 
0 2
|     |     |     |       |     |     |  1 1  |     |     |     |       |
| --- | --- | --- | ----- | --- | --- | ------- | --- | --- | --- | ----- |
|     |     |     |       |     |     | (0,2)   |     |     |     | 2 0 |
|     |     |     |       |     | M   | = 0 3 |     |     |     | M =   |
|     |     |     | (1,1) |     |     |         |     |     |     |     |
1 3
|     |     |     |     |     |     | 3 0 |     |     |     | (3,1) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ----- |
3 1
|     |     |     |     |     | (3,0) |     |     | (2,0) |     |     |
| --- | --- | --- | --- | --- | ----- | --- | --- | ----- | --- | --- |
10 Question
Interpret the first right and left-singular vectors for the following Term-Document Matrix.
|     |     |     |            |     |                | D1              | D2  | D3 D4         | D5  |          |
| --- | --- | --- | ---------- | --- | -------------- | --------------- | --- | ------------- | --- | -------- |
|     |     |     |            |     | complexity     | 2               |     | 3 2           | 3   |          |
|     |     |     |            |     | algorithm      | 3               |     | 4             | 4   |          |
|     |     |     |            |     | entropy        | 1               |     | 2             |     |          |
|     |     |     |            |     | traffic        |                 | 2   |               |     |          |
|     |     |     |            |     | network        |                 |     | 3 1           | 4   |          |
|     |     |     | (Documents |     | → vector-space | representation: |     | term-document |     | matrix.) |
11 Question
Each of the following data sets consists of a subset of the d-dimensional 0/1 vectors labeled +1.
The remaining 0/1 vectors are labeled −1. Which sets are linearly separable?
1. {010,011,100,111}
2. {011,100,110,111}
3. {0100,0101,0110,1000,1100,1101,1110,1111}
| 12    | Exercise |          |     | Sheets | – Questions |        |            |     |     |     |
| ----- | -------- | -------- | --- | ------ | ----------- | ------ | ---------- | --- | --- | --- |
| Sheet | 0        | Exercise |     | 0.1    | (Recall:    | Random | variables) |     |     |     |
(i) Consider the course’s example: A player has a fair die D resulting in one of D :=
1
{1,2,3,4,5,6} with probability each, i.e. D ← D uniformly, and a fair coin C ← {0,1}
6
uniformly.
Actually, our player is a cheater and the coin merely tells whether he decides to cheat or
not. In case the coin comes up heads, say that’s encoded 1, he changes the die’s outcome
|     | to 6. | Denote | the | variable | describing | the faked |     | die by F. |     |     |
| --- | ----- | ------ | --- | -------- | ---------- | --------- | --- | --------- | --- | --- |
3

(a) Describe F as a function of C and D.
(b) Notethatthepair(C,F)isagainarandomvariable,namelywithoutputsin{0,1}×D.
Write down a 2×6-table with its distribution.
(ii) ConsideracontinuousrandomvariableU withoutcomesin[0,1] ⊂ Rwithuniformdensity,
i.e. U ← [0,1] with density p(x) = 1 for x ∈ [0,1] and p(x) = 0 otherwise. Determine the
density of U2, i.e. a function q such that
(cid:90) b
prob (cid:0) a < U2 < b (cid:1) = q(x)dx.
a
Sheet 0 Exercise 0.2 (Maximum of two dice)
Take two independent fair dice D ← D := {1,2,3,4,5,6} and consider the larger outcome
i
M := max(D ,D ).
0 1
(i) Compute prob(M ≤ a) for a ∈ N .
≤6
(ii) Compute prob(M = a) for a ∈ N .
≤6
(iii) Compute E(M).
(iv) Compute E(M2) and derive var(M).
Sheet 1 Exercise 1.1 (Computer scientist’s random variables)
Consider the following algorithm:
1. Throw a coin C ← {0,1}.
2. Choose X ← [0,1] uniformly.
3. Roll a die D ← {1,2,3,4,5,6}.
4. If C = 0 then
5. Let Z ← D+X.
6. Else
7. Let Z ← D−X.
8. Return Z
The output Z of this algorithm is a random variable.
(i) Compute its expectation E(Z).
(ii) Compute its second moment E(Z2).
(iii) Compute its variance var(Z).
Sheet 2 Exercise 2.2 (Annuli)
(i) Compute and estimate the volume of the 1 -annulus compared to the volume of the
100
d-dimensional ball Bd.
(ii) Compute and estimate the volume of the √1 -annulus compared to the volume of the
d
d-dimensional ball Bd.
(iii) Compute and estimate the volume of the 1 -annulus compared to the volume of the d-
d2
dimensional ball Bd.
4

| Sheet | 4   | Exercise | 4.2 | (Eigenvalues |     |     | of graphs) |     |     |
| ----- | --- | -------- | --- | ------------ | --- | --- | ---------- | --- | --- |
(i) What are the eigenvalues of (the adjacency matrices of) the graphs shown below? What
does this say about using eigenvalues to determine whether two graphs are isomorphic?
| Sheet          | 5      | Exercise    | 5.3       | (Eigenvalues |              |              | and -vectors) |           |          |
| -------------- | ------ | ----------- | --------- | ------------ | ------------ | ------------ | ------------- | --------- | -------- |
|                |        |             |          |              |             |              |               |           |          |
|                |        |             | 3         | 0            | 4            |              |               |           |          |
| Take the       | matrix | A =         | 0        | −1           | 0.          |              |               |           |          |
|                |        |             | 4         | 0            | 1            |              |               |           |          |
| (i) Compute    |        | eigenvalues |           | and          | eigenvectors |              | of A.         |           |          |
| (iii) Compute  |        | ∥A∥ 2       | and       | ∥A∥ F        | and compare. |              |               |           |          |
| 13 Theoretical |        |             | Questions |              |              | – Self-Tests |               | for Video | Lectures |
0000 Introduction
| 1000 High-dimensional |     |          | space:    |      | Probabilities |        |              |        |     |
| --------------------- | --- | -------- | --------- | ---- | ------------- | ------ | ------------ | ------ | --- |
| 1010 The              | Law | of Large | Numbers   |      |               |        |              |        |     |
| 1040 Properties       |     | of       | the unit  | ball |               |        |              |        |     |
| 2000 Generating       |     | points   | uniformly |      | at            | random | from a ball  |        |     |
| 2020 Generating       |     | points   | uniformly |      | at            | random | from a ball, | cont’d |     |
2030 Gaussian
| 3020 Symmetric   |     | matrices   |     |                |               |          |                     |     |     |
| ---------------- | --- | ---------- | --- | -------------- | ------------- | -------- | ------------------- | --- | --- |
| 3030 Extremal    |     | properties |     | of eigenvalues |               |          |                     |     |     |
| 3040 Eigenvalues |     | of         | the | sum of         | two symmetric |          | matrices            |     |     |
| 4000 Best-fit    |     | subspaces  | and | SVD:           | Introduction  |          |                     |     |     |
| 4010 Best-fit    |     | subspaces  | and | SVD:           | Singular      |          | vectors             |     |     |
| 4020 Best-fit    |     | subspaces  | and | SVD:           | Singular      |          | value decomposition |     |     |
| 4040 Best-fit    |     | subspaces  | and | SVD:           | Left          | singular | vectors             |     |     |
6020 Applications of SVD: Application 2, principal component analysis, collaborative filtering
| 7000 Machine |     | Learning: |     | Introduction   |     |           |     |     |     |
| ------------ | --- | --------- | --- | -------------- | --- | --------- | --- | --- | --- |
| 7010 Machine |     | Learning: |     | The perceptron |     | algorithm |     |     |     |
7020 Machine Learning: Kernel functions and non-linearly separable data
| 7030 Machine |     | Learning: |     | Generalizing  |     | to new      | data |     |     |
| ------------ | --- | --------- | --- | ------------- | --- | ----------- | ---- | --- | --- |
| 7040 Machine |     | Learning: |     | VC-dimension: |     | Definitions |      |     |     |
5

14 Additional Questions from the Exercise Sheets
Exercise 5.4 (Eigenvalues of sums)
Consider the matrices
(cid:20) (cid:21) (cid:20) (cid:21) (cid:20) (cid:21)
3 0 2 0 cosφ −sinφ
A = Q Q−1, B = , with Q =
0 −1 0 0 sinφ cosφ
for some angle φ.
(i) List the eigenvalues of A and B.
(ii) Take φ = 45◦ = π. Compute the eigenvalues γ of A+B.
4 i
(iii) Compare the results with the theorem and the lemma about sums of symmetric matrices.
Hint: In particular (but not exclusively!), discuss: Is the theorem correct? How large are
the intervals? Would it make sense to swap A and B in the named results?
Exercise 9.3 (Kernels?)
For each of the following maps decide whether it is a kernel. Argue.
• k(|x⟩,|y⟩) = ⟨e |x+y⟩ with the first standard unit vector |e ⟩.
0 0
• k(|x⟩,|y⟩) = ⟨x|y⟩5+17.
• k(|x⟩,|y⟩) = cos⟨x|y⟩.
⟨x|y⟩
• k(|x⟩,|y⟩) = .
(cid:13) (cid:13) (cid:13) (cid:13)
(cid:13)|x⟩(cid:13) (cid:13)|y⟩(cid:13)
2 2
15 Clustering Exercises
CL1. Consider the following dataset in R2: x = (0,0), x = (0,1), x = (−1,2), x =
1 2 3 4
(2,0), x = (3,0), x = (4,−1).
5 6
(i) Compute the distance matrix using the Euclidean (L2) distance.
(ii) Perform 1 iteration of k-means clustering with k = 2, using x and x as the initial cluster
1 6
centers. What are the clusters and new centers?
CL2. Consider the following dataset in R2: x = (0,0), x = (1,0), x = (2,0), x =
1 2 3 4
(−0.5,−1), x = (0.5,−1), x = (0,−1.5).
5 6
(i) ComputethedistancematrixusingtheManhattan(L1)distance. RecallthattheL1 norm
(cid:80)
of a vector is given by ∥x∥ = |x |.
1 i i
(ii) Perform agglomerative hierarchical clustering using single linkage and draw the resulting
dendrogram (does not have to be to scale).
CL3. Let A = {a ,a ,a ,a ,a ,a } with two clusterings:
1 2 3 4 5 6
• C = {C = {a ,a ,a }, C = {a ,a ,a }}
0 0 1 2 1 3 4 5
• C′ = {C = {a ,a ,a }, C = {a ,a ,a }}
0 0 3 4 1 1 2 5
Compute the distance between the two clusterings d(C,C′).
6

R1:
CL4. Given data points in A = 1,2,3,10,11,12 and k = 3. Suppose that in k-means++
initialization, we have selected c 0 = 2 and c 1 = 12. What is the probability distribution for c 2 ?
| 16 VC | Dimension | and | SVMs |     |
| ----- | --------- | --- | ---- | --- |
VC1. Consider the class Ω of axis-parallel hypercubes (intervals, squares, cubes, ...) in
Ω = Rd. This is more restricted than rectangles or hypercuboids! Namely, a hypercube is a
hypercuboid with the additional requirement that all edge lengths are equal.
| 1. Show | that for | d = 1 we have | VCdim(H) | ≥ 2. |
| ------- | -------- | ------------- | -------- | ---- |
| 2. Show | that for | d = 2 we have | VCdim(H) | ≥ 3. |
| 3. Show | that for | d = 3 we have | VCdim(H) | ≥ 4. |
Hint: In each of these cases you have to specify one set of 2,3,5 elements, respectively, and
| prove that | it can be | shattered by | H.  |     |
| ---------- | --------- | ------------ | --- | --- |
R2?
VC2. What is the VC dimension d of a support vector machine in Give arguments why
| (for d ≥   | ... and d ≤ | ...).           |         |     |
| ---------- | ----------- | --------------- | ------- | --- |
| Hint: Draw | pictures    | to support your | claims. |     |
7