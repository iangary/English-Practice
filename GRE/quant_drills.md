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

## Set 2 — Advanced tier (data interpretation + combinatorics)

**Timer: 1:30/question average — 15 minutes for all 10. This set leans
into the two topics that quietly separate Q165 from Q170: multi-step data
interpretation (where the arithmetic is easy but the setup has 2–3 traps)
and combinatorics (where misreading "at least," "exactly," or
"distinct" changes the entire approach).**

**11.** A survey asked 400 employees which of three benefits (Health,
Dental, Vision) they used. 220 used Health, 150 used Dental, 180 used
Vision, 60 used both Health and Dental, 70 used both Health and Vision,
50 used both Dental and Vision, and 25 used all three. How many
employees used none of the three benefits?

**12.** Data Interpretation: A company's quarterly revenue (in $millions)
was: Q1: 40, Q2: 50, Q3: 45, Q4: 65. If Q1 revenue for the following year
increased by 20% over the current year's Q1, and the following year's
total annual revenue grew by exactly 15% over the current year's total,
what was the following year's revenue for Q2+Q3+Q4 combined?

**13.** A committee of 4 people is to be chosen from 6 men and 5 women.
How many different committees are possible if the committee must include
at least 2 women?

**14.** Quantitative Comparison: Set A consists of 7 consecutive even
integers. Set B consists of 7 consecutive odd integers. The median of
Set A equals the median of Set B.

Quantity A: The standard deviation of Set A
Quantity B: The standard deviation of Set B

**15.** A password must consist of exactly 4 characters: 2 distinct
letters (from 26) followed by 2 distinct digits (from 0–9), in that
fixed order (letter-letter-digit-digit). How many distinct passwords are
possible?

**16.** In a certain year, a city's population grew by 10% in the first
half of the year and then declined by 10% in the second half of the
year. If the population at the end of the year was 29,700, what was the
population at the start of the year? (Round to the nearest whole number
if needed.)

**17.** Of the 60 students in a program, 36 study French, 28 study
Spanish, and 10 study neither. How many students study both French and
Spanish?

**18.** A box contains 4 red, 3 blue, and 5 green marbles. If 3 marbles
are drawn at random without replacement, what is the probability that
all 3 are the same color?

**19.** Quantitative Comparison: n is a positive integer and n! (n
factorial) has exactly 2 trailing zeros.

Quantity A: n
Quantity B: 9

**20.** A data set has a mean of 50 and a standard deviation of 8. If
every value in the data set is multiplied by 2 and then increased by 5,
what is the new standard deviation?

---

## Worked Solutions — Set 2

**11. Answer: 5.** Use inclusion-exclusion: |H∪D∪V| = H+D+V −
(H∩D + H∩V + D∩V) + (H∩D∩V) = 220+150+180 − (60+70+50) + 25 =
550 − 180 + 25 = 395. None = 400 − 395 = **5**.

**12. Answer: $182 million.** Current total = 40+50+45+65 = 200.
Next year's total = 200 × 1.15 = 230. Next year's Q1 = 40 × 1.20 = 48.
Q2+Q3+Q4 next year = 230 − 48 = **182**. (Trap: the 20% applies only to
Q1, and the 15% applies to the *total*, not to each quarter individually
— mixing these up is the entire point of this question.)

**13. Answer: 215.** "At least 2 women" means exactly 2, 3, or 4 women
(committee size is 4). Exactly 2 women, 2 men: C(5,2)×C(6,2) = 10×15 =
150. Exactly 3 women, 1 man: C(5,3)×C(6,1) = 10×6 = 60. Exactly 4 women,
0 men: C(5,4)×C(6,0) = 5×1 = 5. Total = 150+60+5 = **215**. (Check
against the complement: total committees of 4 from 11 people = C(11,4) =
330; subtracting the "fewer than 2 women" cases — 0 women: C(6,4)=15,
1 woman: C(5,1)×C(6,3)=5×20=100 — gives 330−15−100 = 215 ✓.)

**14. Answer: (C), they're equal.** Standard deviation depends only on
the *spacing* between values, not on whether the values themselves are
even or odd. Both sets are 7 consecutive integers spaced by 2 (consecutive
evens or consecutive odds both increment by 2), centered on the same
median, so they have identical spread. (Trap: "even" vs. "odd" feels like
it should matter — it doesn't, because spacing, not parity, determines
spread.)

**15. Answer: 58,500.** 2 distinct letters in order: 26 × 25 = 650.
2 distinct digits in order: 10 × 9 = 90. Total = 650 × 90 = **58,500**.
(Trap: it's easy to use 10×10=100 for the digits instead of enforcing
"distinct" on them too — re-read the problem: both the letter pair AND
the digit pair must each be internally distinct.)

**16. Answer: 30,000.** Let P = starting population. P × 1.10 × 0.90 =
29,700 → P × 0.99 = 29,700 → P = 29,700 / 0.99 = **30,000**. (Trap: a 10%
increase followed by a 10% decrease does NOT return to the original value
— it nets to a 1% decrease, since 1.10 × 0.90 = 0.99, not 1.00.)

**17. Answer: 14.** Study French or Spanish (or both) = 60 − 10 = 50.
By inclusion-exclusion: French + Spanish − Both = 50 → 36 + 28 − Both =
50 → Both = 64 − 50 = **14**.

**18. Answer: 3/44.** Total ways to draw 3 from 12: C(12,3) = 220. All
red: C(4,3) = 4. All blue: C(3,3) = 1. All green: C(5,3) = 10. Favorable
= 4+1+10 = 15. Probability = 15/220 = **3/44**.

**19. Answer: (A), Quantity A is greater.** The number of trailing zeros
in n! equals the number of times 5 divides into the product: floor(n/5) +
floor(n/25) + ... For n=9: floor(9/5)=1, so n=9 gives only 1 trailing
zero. For n=10 through n=14: floor(n/5)=2 and floor(n/25)=0, so each
gives exactly 2 trailing zeros (the next multiple of 5 that would add a
third zero is 15). So "n! has exactly 2 trailing zeros" forces n to be
10, 11, 12, 13, or 14 — every valid value of n is greater than 9, so
Quantity A is greater in every case. (The trap: this *looks* like a
"range of values, answer must be (D)" question, since n isn't uniquely
pinned down — but (D) only applies when the relationship actually varies
across the valid range, and here it doesn't: every single valid n beats
9. Always check whether the range as a whole still produces one
consistent comparison before defaulting to (D).)

**20. Answer: 16.** Multiplying every value by a constant k scales the
standard deviation by |k|; adding a constant shifts the mean but does not
change the standard deviation at all. New SD = 8 × 2 = **16** (the "+5"
has zero effect on spread).

### Scoring
8–10/10 = Q168+ pace on the hardest material this program offers · 6–7 =
solid but review combinatorics case-counting specifically · below 6:
this set is intentionally brutal — don't panic, isolate exactly which
*category* (inclusion-exclusion, combinatorics, percent-change traps,
or standard deviation rules) produced your misses and drill that
category alone before retrying the full set.
