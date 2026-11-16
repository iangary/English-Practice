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

# Set 2 — Q165+ pace (18 minutes, 12 questions, 1:30/question)

Faster than Set 1 on purpose. At this level the content isn't harder
math — it's more steps packed into less time, plus traps that only
show up once you stop reading carefully because you're rushing.

## Quantitative Comparison

**1.** n is a positive integer.

Quantity A: n² + n
Quantity B: An even number

**2.** The sequence is defined by a₁ = 3 and a₍ₙ₊₁₎ = 2aₙ − 1 for all n ≥ 1.

Quantity A: a₄
Quantity B: 17

**3.** x² − 5x + 6 = 0

Quantity A: x
Quantity B: 2

## Problem Solving

**4.** In how many ways can 6 people be seated in a row of 6 chairs if
two specific people, A and B, must NOT sit next to each other?

**5.** Pipe A fills a tank in 6 hours. Pipe B fills the same tank in 4
hours. Pipe C, a drain, empties the full tank in 12 hours. Starting
empty, with all three operating simultaneously, how long does it take to
fill the tank?

**6.** Events X and Y are independent. P(X) = 0.6 and P(Y) = 0.5. What
is the probability that at least one of X or Y occurs?

**7.** A positive integer n leaves a remainder of 3 when divided by 7
and a remainder of 2 when divided by 5. What is the remainder when n is
divided by 35?

**8.** The ratio of men to women at a company is 3:5. After the company
hires 10 more men and 10 more women, the new ratio is 2:3. How many
employees worked at the company originally (before the new hires)?

**9.** If 2^(x+1) + 2^x = 96, what is the value of x?

**10.** A committee of 4 is chosen at random from a pool of 6 men and 4
women. What is the probability that the committee includes at least 2
women?

**11.** Given −3 < x < 2 and 1 < y < 4, indicate **all** of the
following that must be true:
(A) x + y < 6
(B) x − y < −2
(C) xy > −15

**12.** A stock's price rises 20% in year 1, falls 25% in year 2, then
rises 50% in year 3. What is the net percent change over the three
years?

---

## Worked Solutions

**1. Answer: (C).** n² + n = n(n+1), the product of two consecutive
integers. One of any two consecutive integers is always even, so the
product is always even, regardless of what n is. (Trap: the fact that
the problem gives you *no information* about n other than "positive
integer" should be your cue to look for something true for *every* such
n — not to assume the comparison is unresolvable.)

**2. Answer: (C).** a₁ = 3, a₂ = 2(3)−1 = 5, a₃ = 2(5)−1 = 9,
a₄ = 2(9)−1 = 17. They're equal.

**3. Answer: (D).** Factor: (x−2)(x−3) = 0, so x = 2 or x = 3. Since x
could equal Quantity B (2) or exceed it (3), the relationship cannot be
determined from the information given.

**4. Answer: 480.** Total arrangements with no restriction = 6! = 720.
Arrangements where A and B sit together: glue them into one block (2
internal orders) with the remaining 4 people: 5! × 2 = 240. Arrangements
where they are NOT adjacent = 720 − 240 = **480**.

**5. Answer: 3 hours.** Rates: A = 1/6, B = 1/4, C = −1/12 (draining).
Combined rate = 1/6 + 1/4 − 1/12 = 2/12 + 3/12 − 1/12 = 4/12 = 1/3 tank
per hour. Time to fill = 1 ÷ (1/3) = **3 hours**.

**6. Answer: 0.8.** P(at least one) = 1 − P(neither) = 1 − (1−0.6)(1−0.5)
= 1 − (0.4)(0.5) = 1 − 0.2 = **0.8**.

**7. Answer: 17.** By the Chinese Remainder Theorem the answer is unique
mod 35. Test n = 17: 17 ÷ 7 = 2 remainder 3 ✓; 17 ÷ 5 = 3 remainder 2 ✓.
Remainder when divided by 35 is **17** (don't overthink this — once you
find any n satisfying both conditions that's less than 35, that IS the
remainder).

**8. Answer: 80.** Let men = 3k, women = 5k. (3k+10)/(5k+10) = 2/3 →
3(3k+10) = 2(5k+10) → 9k+30 = 10k+20 → k = 10. Original men = 30,
women = 50, total = **80**. (Trap: the question asks for the *original*
total, not the total after hiring — rereading what's actually being
asked costs nothing; answering the wrong question costs the whole point.)

**9. Answer: x = 5.** 2^(x+1) + 2^x = 2^x·2 + 2^x = 2^x(2+1) = 3·2^x = 96
→ 2^x = 32 = 2^5 → **x = 5**.

**10. Answer: 23/42 (≈0.548).** Total ways = C(10,4) = 210. At least 2
women = exactly 2 + exactly 3 + exactly 4 women:
exactly 2: C(4,2)×C(6,2) = 6×15 = 90
exactly 3: C(4,3)×C(6,1) = 4×6 = 24
exactly 4: C(4,4)×C(6,0) = 1×1 = 1
Total favorable = 115. Probability = 115/210 = **23/42**.

**11. Answer: (A) and (C) only.** (A): the supremum of x+y is 2+4=6,
never reached since both bounds are strict, so x+y < 6 always holds —
must be true. (B): x−y ranges up to just under 2−1=1 (e.g., x=1.9,
y=1.1 gives x−y=0.8), which is NOT < −2, so (B) is false — a value in
range violates it. (C): the most negative xy can get is as x→−3 and
y→4, approaching −12, which is still greater than −15, so xy > −15
always holds. (Trap: it's tempting to assume all three "look similarly
plausible" from a glance at the bounds — you have to actually test the
extremes of the ranges for each one individually.)

**12. Answer: +35%.** Start at 100. Year 1: 100 × 1.20 = 120. Year 2:
120 × 0.75 = 90. Year 3: 90 × 1.50 = 135. Net change = 135 − 100 = **+35%**.
(Trap: a 20% gain and a 25% loss do not cancel to zero, and the order
and compounding matter — always multiply successive factors, never add
or subtract the percentages directly.)

### Scoring
11–12/12 in 18 minutes = Q168+ pace · 9–10 = Q163–167 · below 9 or over
20 minutes: this set is specifically designed to punish rushing without
rereading — if you missed (1), (8), or (11), that's a reading-the-
question problem, not a math problem. Log which it was in
`PROGRESS_LOG.md`.
