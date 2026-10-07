# GRE Quant — Drill Set

**Timer: 1:45/question average (21 questions in ~47 min across both
quant sections) — for this set of 12, give yourself 21 minutes total, no
calculator beyond the on-screen one the real test provides (basic
arithmetic only, no exponents/roots).**

Read every problem twice before calculating. At this level, the gap
between a 160 and a 168 is almost entirely about catching the trap in
the wording (integer vs. real number, inclusive vs. exclusive, "could be"
vs. "must be") — not about knowing more formulas.

## Quantitative Comparison (compare Quantity A and Quantity B)

Options are always: (A) A is greater, (B) B is greater, (C) they're
equal, (D) relationship cannot be determined from the information given.

**1.** x is an integer and x² < 25.

Quantity A: x
Quantity B: 0

**2.** The average (arithmetic mean) of 5 distinct positive integers is 20.

Quantity A: The largest of the 5 integers
Quantity B: 20

**3.** Circle O has radius 6. Chord AB has length 6.

Quantity A: The length of the arc AB (minor arc)
Quantity B: 2π·(6/3)

## Problem Solving

**4.** A store marks up the wholesale price of an item by 40% to set the
retail price, then later offers a 25% discount off that retail price
during a sale. What percent of the original wholesale price is the sale
price?

**5.** If 3x + 2y = 16 and x − y = 2, what is the value of x + y?

**6.** A rectangular tank with dimensions 4 ft × 3 ft × 2 ft is filled
with water to 75% of its capacity. How many cubic feet of water are in
the tank?

**7.** A jar contains only red and blue marbles in a ratio of 3:5. If 8
more blue marbles are added and no red marbles are added or removed, the
new ratio of red to blue marbles is 1:3. How many red marbles are in the
jar?


**8.** A fair six-sided die is rolled twice. What is the probability that
the sum of the two rolls is greater than 9?

**9.** Data set S consists of the values {4, 7, 7, 9, 13, 40}. If the
value 40 is removed from the data set, which of the following changes?
Indicate all that apply: (A) the mean (B) the median (C) the range

**10.** A car travels 180 miles at an average speed of 60 mph for the
first part of a trip, then travels the remaining 120 miles at an average
speed of 40 mph. What is the car's average speed, in mph, for the entire
trip?

**11.** If a² = 49 and b³ = −8, what is the greatest possible value of
a − b?

**12.** A survey of 200 people found that 120 like coffee, 90 like tea,
and 50 like both. How many people like neither coffee nor tea?

---

## Worked Solutions

**1. Answer: (D).** x² < 25 means −5 < x < 5, so x could be any integer
from −4 to 4, including negative values, 0, or positive values. Since x
could be greater than, less than, or equal to 0, the relationship cannot
be determined. (Trap: it's tempting to assume x is positive because it's
"x," not because the problem says so.)

**2. Answer: (A).** Five *distinct* positive integers averaging 20 sum to
100. To minimize the largest value, make the other four as large as
possible while staying below it: e.g., 18, 19, 20... wait — they must be
distinct and the mean is fixed at 20, so if the largest were exactly 20,
the other four would need to average slightly above 20 while all being
smaller than 20 — impossible. So the largest must exceed 20 to balance
four smaller distinct integers. Quantity A > Quantity B.

**3. Answer: (B).** Chord AB = 6 = radius, so triangle OAB is equilateral
(all sides = 6), making the central angle 60°, i.e., 1/6 of the circle.
Arc length = (1/6)(2π·6) = 2π. Quantity B = 2π·2 = 4π. So B > A.

**4. Answer: 105%.** Wholesale = 100. Retail = 100 × 1.40 = 140. Sale
price = 140 × 0.75 = 105. 105 is 105% of the original wholesale price.
(Trap: a 40% markup followed by a 25% discount does NOT cancel out to
the original price — multiply the factors, don't subtract the percentages.)

**5. Answer: x + y = 6.** From x − y = 2, x = y + 2. Substitute into
3x + 2y = 16: 3(y+2) + 2y = 16 → 3y + 6 + 2y = 16 → 5y = 10 → y = 2,
x = 4. Check: 3(4)+2(2) = 12+4 = 16 ✓, x−y = 4−2 = 2 ✓. x + y = 4+2 = **6**.

**6. Answer: 18 cubic feet.** Full capacity = 4×3×2 = 24 cubic feet.
75% of 24 = 18.

**7. Answer: 6 red marbles.** Let red = 3k, blue = 5k. After adding 8
blue: 3k / (5k+8) = 1/3 → 9k = 5k + 8 → 4k = 8 → k = 2. Red = 3k = 6.
Check: blue = 5(2)=10, +8 = 18, ratio 6:18 = 1:3 ✓.

**8. Answer: 1/6.** Sums greater than 9 means sums of 10, 11, or 12.
Out of 36 equally likely outcomes: sum=10 has 3 ways (4-6,5-5,6-4),
sum=11 has 2 ways (5-6,6-5), sum=12 has 1 way (6-6). Total = 6 ways.
Probability = 6/36 = 1/6.

**9. Answer: (A), (B), and (C) all change.** Original sorted set:
4,7,7,9,13,40 (n=6) — median = (7+9)/2 = 8. Remove 40: 4,7,7,9,13 (n=5)
— median = 7. So the median changes along with the mean (40 was a large
outlier) and the range (40−4=36 shrinks to 13−4=9). The trap: it's easy
to assume removing an extreme value only affects the mean and range,
but going from an even count to an odd count changes which values get
averaged for the median too — check parity before assuming it's safe.

**10. Answer: 50 mph.** Total distance = 180+120 = 300 miles. Time for
first part = 180/60 = 3 hours. Time for second part = 120/40 = 3 hours.
Total time = 6 hours. Average speed = 300/6 = 50 mph. Note: average
speed is always total distance over total time, never a simple average
of the two speeds — that it also equals (60+40)/2 here is a coincidence
of these particular numbers, not a shortcut you can rely on in general.

**11. Answer: 9.** a² = 49 → a = 7 or −7. b³ = −8 → b = −2 (the only real
cube root). To maximize a − b, maximize a and minimize −b, i.e., take the
largest a (7) and the most negative b is already fixed at −2 (cube roots
of negative numbers have only one real solution, unlike square roots).
a − b = 7 − (−2) = 9.

**12. Answer: 40 people.** Like coffee or tea (or both) = 120 + 90 − 50
(both, counted twice) = 160. Neither = 200 − 160 = 40.

### Habit to keep

Every solution above that involves solving an equation includes a
plug-back-in check. Make that automatic in your own work, not optional —
it's the single habit most responsible for closing the gap between
knowing the method and reliably getting the point under time pressure.

### Scoring
11–12/12 = Q165+ pace · 9–10 = Q160–164 · below 9: sort your misses into
"careless" (knew the method, slipped on execution — drill verification
habits) vs. "conceptual" (didn't know the approach — review that specific
topic) in `PROGRESS_LOG.md`. These need entirely different fixes.

---

## Drill Set 2 — Harder, Tighter Clock

**Timer: 1:30/question average — 18 minutes total for these 12, no
exceptions.** This set assumes Set 1 is already comfortable at or under
pace. If you haven't hit 11/12 on Set 1 twice, finish that before
starting this — a faster clock on unmastered material just trains panic,
not speed.

### Quantitative Comparison

**1.** x > 0, y > 0, x² + y² = 25, and xy = 12.

Quantity A: x + y
Quantity B: 7

**2.** n is an odd positive integer.

Quantity A: the remainder when n² is divided by 8
Quantity B: 1

**3.** n is an integer greater than 1. Set S = {2, 4, 6, ..., 2n}. Set T =
{1, 2, 3, ..., n}.

Quantity A: the standard deviation of S
Quantity B: the standard deviation of T

### Problem Solving

**4.** A committee of 4 people is to be chosen from 6 men and 5 women.
How many such committees contain at least 2 women?

**5.** Working alone, Machine A completes a job in 6 hours and Machine B
completes the same job in 10 hours. Machine A works alone for 2 hours,
then Machine B joins and they finish the job together. How many hours,
total, does the job take from start to finish?

**6.** What is the largest integer k such that 10! is divisible by 2^k?

**7.** A sequence is defined by a₁ = 3 and a(n+1) = 2·a(n) − 1. What is a₅?

**8.** If |2x − 5| ≤ 7, what is the range of possible values of x?

**9.** In a group of 150 students, 90 study French, 70 study Spanish, and
20 study neither language. How many students study both?

**10.** A right circular cylinder has radius 3 and volume 54π. What is
its total surface area (both circular bases included)?

**11.** The ratio of a to b is 2:3, and the ratio of b to c is 4:5. What
is the ratio of a to c?

**12.** x is a positive integer chosen from {1, 2, 3, ..., 10}. What is
the probability that x³ ≤ 1000?

---

### Worked Solutions — Set 2

**1. Answer: (C).** (x+y)² = x² + y² + 2xy = 25 + 24 = 49, so x + y = 7
(positive, since x, y > 0). Equal.

**2. Answer: (C).** This is a fact worth memorizing outright: the square
of any odd integer is always ≡ 1 (mod 8). Check it: 1²=1, 3²=9 (rem 1),
5²=25 (rem 1), 7²=49 (rem 1) — the pattern holds for every odd n. Equal.

**3. Answer: (A).** S = 2·T element-wise, and multiplying every value in
a data set by a constant c multiplies the standard deviation by |c| (it
does **not** add or get affected by the shift the way the mean would).
So SD(S) = 2·SD(T), which is strictly greater than SD(T) as long as
SD(T) > 0 — guaranteed here since n > 1 means T has at least two distinct
values. (Trap: this only works because it's a pure scaling, not a shift —
"add 2 to every value" would leave the SD unchanged instead.)

**4. Answer: 215.** Total ways to pick any 4 from 11: C(11,4) = 330.
Subtract the cases with fewer than 2 women. Zero women: C(6,4) = 15. One
woman: C(5,1)·C(6,3) = 5·20 = 100. At least 2 women = 330 − 15 − 100 =
**215**. (Complementary counting is faster here than summing the "exactly
2," "exactly 3," "exactly 4 women" cases directly — recognize the signal:
"at least" with more than one excluded case usually means subtract instead
of add.)

**5. Answer: 4.5 hours.** Rate A = 1/6 job/hr. In 2 hours alone, A
completes 2/6 = 1/3 of the job, leaving 2/3. Combined rate once B joins =
1/6 + 1/10 = 5/30 + 3/30 = 8/30 = 4/15 job/hr. Time to finish the
remaining 2/3 together = (2/3) ÷ (4/15) = (2/3)·(15/4) = 30/12 = 2.5
hours. Total = 2 + 2.5 = **4.5 hours**.

**6. Answer: 8.** Use Legendre's formula for the exponent of a prime p in
n!: sum of floor(n/p), floor(n/p²), ... for 10! and p=2: floor(10/2) +
floor(10/4) + floor(10/8) = 5 + 2 + 1 = **8**.

**7. Answer: 33.** a₁=3 → a₂=2(3)−1=5 → a₃=2(5)−1=9 → a₄=2(9)−1=17 →
a₅=2(17)−1=**33**. (Recursive sequence questions are pure execution —
the only way to miss this is an arithmetic slip, so write out every step,
don't try to shortcut it in your head.)

**8. Answer: −1 ≤ x ≤ 6.** |2x−5| ≤ 7 means −7 ≤ 2x−5 ≤ 7. Add 5:
−2 ≤ 2x ≤ 12. Divide by 2: **−1 ≤ x ≤ 6**.

**9. Answer: 30.** At least one of French/Spanish = 150 − 20 = 130.
French + Spanish − both = at least one, so 90 + 70 − both = 130, giving
both = **30**.

**10. Answer: 54π.** V = πr²h = 54π with r=3 → 9h = 54 → h = 6. Surface
area = 2πr² + 2πrh = 2π(9) + 2π(3)(6) = 18π + 36π = **54π**. (Notice the
surface area and volume come out to the same numeric coefficient here —
that's a coincidence of these specific numbers, not a shortcut; always
compute both from scratch.)

**11. Answer: 8/15.** a/c = (a/b)·(b/c) = (2/3)·(4/5) = **8/15**.

**12. Answer: 1.** 10³ = 1000 exactly, and every integer from 1 to 10
cubed is ≤ 1000 (the largest, 10³, hits the boundary exactly and the
condition is ≤, not <). Every value in the set satisfies the condition,
so the probability is **1**. (This is a deliberate trap: it's tempting to
assume a "probability" question must have a fractional answer and start
hunting for exceptions that don't exist — read the condition and the
range before assuming the question wants you to exclude anything.)

### Scoring — Set 2
10–12/12 under the 18-minute clock = genuinely Q165+ ready. 7–9 = the
concepts are there but pace isn't — rerun this exact set in 3 days before
moving to new material. Below 7 = at least one topic above (probability,
counting, sequences, or the scaling-vs-shift distinction in #3) needs
direct review, not just more timed reps.
