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

### Scoring, Set 1
11–12/12 = Q165+ pace · 9–10 = Q160–164 · below 9: sort your misses into
"careless" (knew the method, slipped on execution — drill verification
habits) vs. "conceptual" (didn't know the approach — review that specific
topic) in `PROGRESS_LOG.md`. These need entirely different fixes.

---

## Set 2 — harder, with Data Interpretation (21 minutes, 12 questions)

Don't touch this set until Set 1 is at 11/12 or better twice in a row.
These questions compress 2–3 steps into one stem, the way the real
165+ range does — there's no single "trick," just more arithmetic you
have to carry correctly across more steps without a scratch-pad error.

**13.** A town's population grew by 20% in year 1 and then declined by
15% in year 2. If the population at the end of year 2 was 20,400, what
was the population at the start of year 1?

**14.** x and y are positive integers and 2^x · 3^y = 648.

Quantity A: x + y
Quantity B: 6

**15.** The ratio of men to women at a conference is 5:7. After 20 more
women arrive and no men leave or arrive, the ratio becomes 5:9. How many
men are at the conference?

**16.** A set of 7 numbers has a mean of 15. If one number is removed,
the mean of the remaining 6 numbers is 14. What was the number removed?

**Data Interpretation (Q17–19): A survey asked 500 employees which of
three benefits they valued most: Remote Work (R), Higher Salary (S), or
More PTO (P). Results: R only = 140, S only = 110, P only = 90,
R and S only = 45, R and P only = 35, S and P only = 25, all three = 15,
none of the three = 40.**

**17.** How many employees valued Remote Work (in any combination)?

**18.** What percent of the 500 employees valued exactly two of the
three benefits?

**19.** How many employees valued Higher Salary OR More PTO (or both),
but NOT Remote Work?

**20.** A machine produces widgets at a constant rate and can complete a
production run in 8 hours. A second, newer machine can complete the same
run in 5 hours. If both machines work together, starting at the same
time, how many hours will it take to complete the run? (Express as a
fraction.)

**21.** For how many integer values of n is 3 < |2n − 5| < 15 true?

**22.** The probability that event A occurs is 0.4. The probability that
event B occurs is 0.5. If A and B are independent, what is the
probability that at least one of them occurs?

**23.** A rectangle's length is increased by 25% and its width is
decreased by x%. If the rectangle's area is unchanged, what is x?

**24.** List L consists of 8 integers with a range of 20 and a median of
10. What is the minimum possible value of the smallest integer in L?

---

### Worked Solutions, Set 2

**13. Answer: 20,000.** Let P = starting population. P × 1.20 × 0.85 =
20,400 → P × 1.02 = 20,400 → P = 20,000. (Trap: don't average the +20%
and −15% into a single +5%/−5% shortcut — percent changes compound
multiplicatively, not additively; 1.20 × 0.85 = 1.02, not 1.05.)

**14. Answer: (A).** 648 = 8 × 81 = 2³ × 3⁴, so x = 3, y = 4, x + y = 7.
Quantity A (7) > Quantity B (6).

**15. Answer: 50 men.** Let men = 5k, women = 7k. (5k)/(7k+20) = 5/9 →
45k = 35k + 100 → 10k = 100 → k = 10. Men = 5k = 50. Check: women =
7(10)+20 = 90, ratio 50:90 = 5:9 ✓.

**16. Answer: 21.** Sum of 7 numbers = 7×15 = 105. Sum of remaining 6 =
6×14 = 84. Removed number = 105 − 84 = 21.

**17. Answer: 235.** R only (140) + R∩S only (45) + R∩P only (35) + all
three (15) = 140+45+35+15 = 235.

**18. Answer: 21%.** Exactly two = (R∩S only) + (R∩P only) + (S∩P only)
= 45+35+25 = 105. 105/500 = 21%. (Trap: "all three" is exactly three,
not two — don't include the 15 here.)

**19. Answer: 225.** Need S or P (any combination) but NOT R. The three
groups that involve S or P without R are: S only (110), P only (90), and
S∩P only (25) — by definition none of these three includes R. Sum =
110+90+25 = **225**.

**20. Answer: 40/13 hours.** Combined rate = 1/8 + 1/5 = 5/40 + 8/40 =
13/40 (job/hour). Time = 1 ÷ (13/40) = 40/13 hours (≈ 3.08 hours).

**21. Answer: 10.** 3 < |2n−5| < 15 splits into two cases. Case 1:
2n−5 > 3 → n > 4, and 2n−5 < 15 → n < 10, so n ∈ {5,6,7,8,9}. Case 2:
2n−5 < −3 → n < 1, and 2n−5 > −15 → n > −5, so n ∈ {−4,−3,−2,−1,0}.
Total valid integers = 5 + 5 = 10. (Double-check your own boundary
inclusivity here — this is exactly the kind of count that's easy to be
off-by-one on.)

**22. Answer: 0.7.** P(at least one) = 1 − P(neither) = 1 −
[(1−0.4)(1−0.5)] = 1 − (0.6×0.5) = 1 − 0.3 = 0.7.

**23. Answer: 20%.** Let original dimensions be L and W, area = LW. New
area = 1.25L × (1−x/100)W = LW → 1.25 × (1−x/100) = 1 → 1−x/100 = 0.8 →
x/100 = 0.2 → x = 20.

**24. Answer: −10.** Sort the 8 values a1≤…≤a8. Median = (a4+a5)/2 = 10,
so a4+a5 = 20 with a4 ≤ 10 ≤ a5. Range: a8 − a1 = 20, so a8 = a1 + 20.
Since a5 ≤ a8, we get a5 ≤ a1 + 20. Combined with a5 ≥ 10 (from
a4 ≤ a5 and a4+a5=20), that forces a1 + 20 ≥ 10, i.e., a1 ≥ −10. This is
achievable: {−10, 10, 10, 10, 10, 10, 10, 10} has range 20 and median
(10+10)/2 = 10. (Trap: the range constraint links the smallest value
directly to the largest, and the largest can't dip below the median
values above it — don't treat "minimize the smallest" as unconstrained
just because the problem doesn't mention the largest directly.)

### Scoring, Set 2
10–12/12 = Q168+ pace · 7–9 = Q163–167 · below 7: this set is calibrated
harder than Set 1 on purpose — don't panic at a lower raw score, but do
log every miss by *which specific step* broke (not just "got it wrong")
in `PROGRESS_LOG.md`, since multi-step problems usually fail at one
identifiable link, not the whole chain.
