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

## Set 2 — Higher Difficulty

**Timer: 1:30/question — tighter than Set 1. 12 questions, 18 minutes
total, hard stop. This set assumes Set 1 is already comfortable; if you
scored below 9/12 on Set 1, redo Set 1 before attempting this one — more
time pressure on shaky fundamentals just trains panic, not skill.**

### Quantitative Comparison

**1.** x and y are positive integers and x^y = y^x, with x ≠ y.

Quantity A: x + y
Quantity B: 6

**2.** Set T consists of the first 10 positive multiples of 6.

Quantity A: The median of Set T
Quantity B: The average (arithmetic mean) of Set T

**3.** 0 < r < 1 < s

Quantity A: r/s
Quantity B: s/r

### Problem Solving

**4.** A cylindrical tank with radius 3 and height 10 is filled with
water. The water is then poured, without loss, into a second cylindrical
tank with radius 5. To the nearest tenth, what is the height of the
water in the second tank?

**5.** In a certain office, the ratio of managers to employees is 2:9.
If 4 managers and 6 employees are added, the new ratio of managers to
employees becomes 1:3. How many managers were originally in the office?

**6.** How many integers between 1 and 500, inclusive, are divisible by
either 6 or 8 (or both)?

**7.** A committee of 4 people is to be chosen from a group of 6 men and
5 women. What is the probability that the committee includes exactly 2
men and 2 women?

**8.** The function f is defined by f(x) = x² − 6x + k, where k is a
constant. If f has exactly one real root, what is the value of k?

**9.** A merchant buys an item for $80 and wants a profit of 25% on the
*selling* price (not the cost). What selling price should she set?

**10.** Data set S has a standard deviation of 4 and a mean of 50. If
every value in S is multiplied by 3 and then increased by 5, what is the
new standard deviation?

**11.** Working alone, Pump A can fill a tank in 6 hours; Pump B can fill
the same tank in 4 hours. Both pumps start together, but Pump A is shut
off after 2 hours. How much additional time does Pump B need, working
alone, to finish filling the tank?

**12.** If n is a positive integer and n! has exactly 2 trailing zeros,
what is the smallest possible value of n?

---

## Set 2 — Worked Solutions

**1. Answer: (C).** The only positive integers with x ≠ y satisfying
x^y = y^x are {x, y} = {2, 4} (2^4 = 4^2 = 16). So x + y = 6 always,
meaning Quantity A equals 6 — the same as Quantity B. (This is a classic
GRE trap: test-takers assume "the relationship can't be determined" or
guess "greater than" without actually hunting for the unique case that
satisfies an unusual equation like this.)

**2. Answer: (C).** Set T = {6,12,18,24,30,36,42,48,54,60}. It's evenly
spaced, so median = mean = 33 for any evenly spaced set with an even
number of terms (average of the two middle terms (30+36)/2 = 33; mean =
sum/10 = 330/10 = 33). Equal.

**3. Answer: (B).** Since 0 < r < 1 < s, r/s is a fraction less than 1
(small number divided by a bigger number), while s/r is greater than 1
(big number divided by a smaller fraction). So s/r > r/s always.

**4. Answer: 3.6.** Volume is conserved: π(3)²(10) = π(5)²(h) → 90 = 25h
→ h = 3.6.

**5. Answer: 4 managers.** Let managers = 2k, employees = 9k. After
adding 4 managers and 6 employees: (2k+4)/(9k+6) = 1/3 → 3(2k+4) = 9k+6
→ 6k+12 = 9k+6 → 6 = 3k → k = 2. Original managers = 2k = 4. Check:
original employees = 9(2) = 18; after adding, managers = 8, employees =
24, ratio 8:24 = 1:3 ✓.

**6. Answer: 125.** Multiples of 6 up to 500: ⌊500/6⌋ = 83 (6×83=498).
Multiples of 8: ⌊500/8⌋ = 62 (8×62=496). Multiples of both, i.e. of
lcm(6,8)=24: ⌊500/24⌋ = 20 (24×20=480, 24×21=504 is too big). By
inclusion-exclusion: 83 + 62 − 20 = 125.

**7. Answer: 5/11.** Total committees of 4 from 11 people: C(11,4) =
330. Committees with exactly 2 men and 2 women: C(6,2)×C(5,2) = 15×10 =
150. Probability = 150/330 = 5/11.

**8. Answer: k = 9.** Exactly one real root means the discriminant is 0:
(−6)² − 4(1)(k) = 0 → 36 − 4k = 0 → k = 9.

**9. Answer: $106.67 (to the nearest cent, $320/3).** "25% profit on
selling price" means cost = 75% of selling price: 80 = 0.75 × SP → SP =
80/0.75 = 106.666... This is the classic trap distinguishing margin
(percent of selling price) from markup (percent of cost) — read which
one the question specifies every time.

**10. Answer: 12.** Multiplying every value by a constant c scales the
standard deviation by |c|; adding a constant shifts the mean but does not
change the spread. New SD = 4 × 3 = 12 (the "+5" is a distractor with
zero effect on standard deviation).

**11. Answer: 2/3 hour (40 minutes).** Pump A's rate = 1/6 tank/hr,
Pump B's rate = 1/4 tank/hr. In 2 hours together: 2(1/6 + 1/4) =
2(5/12) = 5/6 of the tank filled. Remaining = 1/6. Pump B alone needs
(1/6)/(1/4) = 4/6 = 2/3 hour to finish.

**12. Answer: n = 10.** Trailing zeros in n! come from factors of 5 (5s
are scarcer than 2s). 9! has one factor of 5 (from 5), giving 1 trailing
zero. 10! adds another factor of 5 (from 10 = 2×5), giving 2 trailing
zeros. So n = 10 is the smallest value with exactly 2 trailing zeros.

### Scoring
10–12/12 at 1:30/question = genuine Q165+ pace. Below that, the issue is
very likely speed, not knowledge — redo Set 1 untimed first to confirm
you actually know every method, then retime Set 1, then come back here.
