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

# GRE Quant — Drill Set 2

**Same timer: 21 minutes for these 12 questions, on-screen calculator
only.** This set leans harder on data interpretation and algebra traps —
the two areas where a Q160 test-taker and a Q168 test-taker most
visibly diverge.

## Quantitative Comparison

**1.** x and y are integers. x > y > 0.

Quantity A: x/y
Quantity B: (x+1)/(y+1)

**2.** The sum of three consecutive even integers is 90.

Quantity A: The smallest of the three integers
Quantity B: 28

**3.** A rectangle has perimeter 28 and area 48.

Quantity A: The length of the longer side
Quantity B: 12

## Problem Solving

**4.** A company's revenue grew by 20% in Year 1 and then fell by 20% in
Year 2. What was the net percent change in revenue over the two years?

**5.** If 5 machines can produce 100 units in 4 hours, how many hours
would it take 8 machines, working at the same constant rate, to produce
280 units?

**6.** Set T consists of the integers from 1 to 50, inclusive. How many
integers in T are divisible by either 4 or 6 (or both)?

**7.** A solution is 30% acid by volume. How many liters of pure water
must be added to 20 liters of this solution to dilute it to a 12% acid
solution?

**8.** In a class of 30 students, the ratio of students who passed to
students who failed is 5:1. If 3 more students had passed and 3 fewer
had failed, what would the new ratio of passed to failed be?

**9.** What is the sum of all integers from 1 to 100 that are NOT
multiples of 5?

**10.** A right triangle has legs of length 9 and 12. A circle is
inscribed in the triangle (tangent to all three sides). What is the
radius of the inscribed circle?

**11.** Working alone, Pump A can fill a tank in 6 hours. Working alone,
Pump B can fill the same tank in 4 hours. If Pump A works alone for 1
hour before Pump B joins it, how much additional time, in hours, is
needed for both pumps working together to finish filling the tank?

**12.** A data set of 7 distinct integers has a median of 20 and a range
of 10. What is the least possible value of the largest integer in the
set?

---

## Worked Solutions

**1. Answer: (A).** Since x > y > 0, x/y is some ratio greater than 1.
Adding 1 to both numerator and denominator always moves a ratio greater
than 1 *closer to* 1 (e.g., 3/1=3 vs 4/2=2) — it never flips which is
bigger. So x/y > (x+1)/(y+1) for any x > y > 0. Quantity A is greater.
(Trap: don't assume adding the same amount to both doesn't change a
ratio — it does, predictably, toward 1.)

**2. Answer: (C).** Let the integers be n, n+2, n+4. Sum = 3n+6 = 90 →
n = 28. The smallest is 28, which equals Quantity B exactly — the
quantities are equal. (This is a deliberate reminder: always finish the
arithmetic before answering — "looks like A because it's the smallest
in a growing sequence" is not a solution.)

**3. Answer: (B).** Let sides be L and W. 2(L+W)=28 → L+W=14. LW=48.
Solving: L and W are roots of t² − 14t + 48 = 0 → (t−6)(t−8)=0, so sides
are 6 and 8. The longer side is 8, which is less than 12, so Quantity B
is greater. (Trap: don't assume the "longer side" of a rectangle with
this perimeter must be large — solve the system before comparing.)

**4. Answer: −4%.** Let revenue start at 100. Year 1: 100 × 1.20 = 120.
Year 2: 120 × 0.80 = 96. Net change = 96 − 100 = −4, i.e., a 4% decrease.
(Trap: a 20% gain and a 20% loss do not cancel out, because the second
percentage applies to a different base.)

**5. Answer: 7 hours.** Rate per machine = 100/(5×4) = 5 units/hour.
8 machines produce 8×5 = 40 units/hour. Time for 280 units =
280/40 = 7 hours. (Equivalently: 5 machines × 4 hours = 20 machine-hours
for 100 units, so 280 units need 56 machine-hours; 56/8 = 7 hours.)

**6. Answer: 16.** Multiples of 4 from 1–50: 12 (4,8,...,48). Multiples
of 6: 8 (6,12,...,48). Multiples of both 4 and 6 (i.e., of 12): 4
(12,24,36,48). By inclusion-exclusion: 12 + 8 − 4 = 16. (This is the
classic inclusion-exclusion trap: forgetting to subtract the overlap
double-counts the multiples of 12.)

**7. Answer: 30 liters.** Pure acid in original solution = 20 × 0.30 =
6 liters. After adding x liters of water, total volume = 20+x, and acid
is still 6 liters, now at 12%: 6/(20+x) = 0.12 → 20+x = 50 → x = 30.

**8. Answer: 14:1.** 30 students, ratio 5:1 passed to failed means 25
passed, 5 failed. Shifting 3 (passed: 25→28, failed: 5→2): new ratio =
28:2 = 14:1.

**9. Answer: 4000.** Sum of 1 to 100 = 100×101/2 = 5050. Multiples of 5
from 1–100: 5,10,...,100 — that's 20 terms, sum = 5×(1+2+...+20) =
5×210 = 1050. Non-multiples of 5 sum = 5050 − 1050 = 4000.

**10. Answer: 3.** Hypotenuse = √(9²+12²) = √(81+144) = √225 = 15. For a
right triangle, inradius r = (leg1 + leg2 − hypotenuse)/2 =
(9+12−15)/2 = 6/2 = 3.

**11. Answer: 2 hours.** Pump A's rate = 1/6 tank/hour, Pump B's rate =
1/4 tank/hour. After A works alone for 1 hour, 1/6 of the tank is full,
leaving 5/6. Combined rate = 1/6+1/4 = 2/12+3/12 = 5/12 tank/hour. Time
to finish 5/6 at that rate = (5/6)/(5/12) = (5/6)×(12/5) = 2 hours.

**12. Answer: 23.** Sorted, the 7 distinct integers are v1<v2<v3<v4<v5<v6<v7,
with median v4 = 20 and range v7−v1 = 10. We want to minimize v7. Since
v5, v6, v7 must be three *distinct* integers all greater than 20, the
smallest they can possibly be is 21, 22, 23 — so v7 ≥ 23 no matter what.
Can v7 = 23 actually be achieved while also satisfying the range
constraint (v1 = v7−10 = 13) and fitting two distinct integers strictly
between v1=13 and v4=20 (e.g., 14, 15)? Yes: the set {13, 14, 15, 20,
21, 22, 23} is valid — 7 distinct integers, median 20, range 23−13=10.
So the true minimum is **23**. (Flagged as the hardest question in this
set: the trap is minimizing v1 instead of recognizing that v7 is bounded
below by the three distinct values that must exceed the median,
independent of the range constraint — the range constraint only matters
for confirming a valid v1 exists, which it does here.)

### Scoring
10–12/12 = Q165+ pace, but review #2, #3, and #12 carefully even if you
got them right — each one has a one-step trap (stopping before finishing
the arithmetic, assuming "longer side" implies large, or anchoring on
the wrong variable to minimize). 7–9 = solid, keep drilling algebraic
word problems. Below 7: stop doing new questions and instead redo Set 1
untimed, talking through your reasoning out loud.
