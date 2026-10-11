# GRE Quant — Drill Set 2 (Harder)

**Timer: 1:45/question average — for this set of 12, give yourself 21
minutes total, no calculator beyond the on-screen one the real test
provides (basic arithmetic only, no exponents/roots).**

This set leans harder on combinatorics, data interpretation reasoning,
and multi-step algebra than Set 1. If you haven't scored 10+/12 on
`quant_drills.md` (Set 1) under full time pressure, redo that set first —
drilling harder material before the basics are automatic just teaches you
to be slow at hard problems instead of fast at easy ones.

## Quantitative Comparison

**1.** x and y are positive integers and x/y = 0.6.

Quantity A: The remainder when x is divided by y
Quantity B: 0

**2.** Set A = {3, 6, 9, 12, 15}. Set B consists of all possible sums of
two distinct elements from Set A.

Quantity A: The number of distinct values in Set B
Quantity B: 10

**3.** A positive integer n is divisible by both 6 and 8.

Quantity A: n
Quantity B: 24

## Problem Solving

**4.** A committee of 4 people is to be chosen from a group of 6 men and
5 women. How many different committees are possible that contain exactly
2 men and 2 women?

**5.** Machine A can complete a job in 6 hours working alone. Machine B
can complete the same job in 4 hours working alone. If both machines work
together but Machine A stops after 2 hours while Machine B continues
alone until the job is finished, how many total hours does the job take?

**6.** The data below shows a company's quarterly profit (in millions of
dollars) for four quarters: Q1 = 2.4, Q2 = 3.1, Q3 = 1.8, Q4 = 4.3. The
company's profit target for the year was for the average quarterly profit
to exceed $3.0 million. By how many millions of dollars did the actual
average quarterly profit fall short of (or exceed) this target?

**7.** If (x − 3)(x + 5) = 0 and (y + 2)(y − 7) = 0, what is the greatest
possible value of xy?

**8.** A bag contains 4 red chips, 3 blue chips, and 5 green chips. If two
chips are drawn at random without replacement, what is the probability
that both chips are the same color?

**9.** In a certain school, 65% of students take French, 45% take
Spanish, and 20% take both. What percent of students take neither?

**10.** A circle is inscribed in a square such that the circle touches
all four sides of the square. If the square has an area of 64, what is
the area of the circle, in terms of π?

**11.** The ratio of boys to girls in a class is 5:4. After 6 more girls
join the class and no boys leave or join, the new ratio of boys to girls
is 5:6. How many boys are in the class?

**12.** A sequence is defined by a₁ = 3 and aₙ = 2aₙ₋₁ − 1 for n > 1.
What is a₅?

---

## Worked Solutions

**1. Answer: (B).** x/y = 0.6 = 3/5, so x = 3k and y = 5k for some
positive integer k (in lowest terms, x and y must be in ratio 3:5, though
k could be any positive integer making x,y integers — e.g., x=3,y=5 or
x=6,y=10). In every case, x < y, so when x is divided by y the quotient
is 0 and the remainder is x itself, which is a positive integer, hence
greater than 0. Quantity B is greater. (Trap: don't assume "remainder"
must be small or confuse it with the decimal 0.6 itself.)

**2. Answer: (B).** Don't trust intuition here — list every pair
systematically: 3+6=9, 3+9=12, 3+12=15, 3+15=18, 6+9=15, 6+12=18,
6+15=21, 9+12=21, 9+15=24, 12+15=27. Distinct sums: {9,12,15,18,21,24,27}
= 7 distinct values. Quantity A = 7 < Quantity B = 10, so **(B) is
greater**. (Trap: with 5 elements there are C(5,2)=10 pairs, and it's
tempting to assume 10 pairs means 10 distinct sums — several sums repeat,
which is exactly why you list them instead of estimating.)

**3. Answer: (D).** Divisible by both 6 and 8 means divisible by their
LCM, which is 24. So n could be 24, 48, 72, etc. — n is a multiple of 24,
but not necessarily equal to 24. Could be greater (48) or equal (24), so
the relationship cannot be determined.

**4. Answer: 150.** Choose 2 men from 6: C(6,2) = 15. Choose 2 women from
5: C(5,2) = 10. Total committees = 15 × 10 = 150.

**5. Answer: 8/3 hours (≈2.67 hours).** Machine A's rate = 1/6 job/hr,
Machine B's rate = 1/4 job/hr. In the first 2 hours working together,
they complete 2×(1/6 + 1/4) = 2×(2/12+3/12) = 2×(5/12) = 10/12 = 5/6 of
the job. Remaining job = 1 − 5/6 = 1/6. Machine B alone finishes the
remaining 1/6 at rate 1/4 job/hr, taking (1/6)/(1/4) = 4/6 = 2/3 hour.
Total time from start = 2 hours (both working) + 2/3 hour (B alone) =
**8/3 hours**. (Trap: it's tempting to stop at "5/6 done after 2 hours"
and forget to convert the *remaining* fraction into time using B's rate,
not a flat guess like "it's almost done, call it 2.5.")

**6. Answer: Fell short by $0.1 million.** Average = (2.4+3.1+1.8+4.3)/4
= 11.6/4 = 2.9. Target was 3.0. Shortfall = 3.0 − 2.9 = **$0.1 million
short**.

**7. Answer: 21.** (x−3)(x+5)=0 → x = 3 or x = −5. (y+2)(y−7)=0 → y = −2
or y = 7. To maximize xy, test all four combinations: 3×7=21, 3×(−2)=−6,
(−5)×7=−35, (−5)×(−2)=10. Greatest value among these = **21**. (Trap:
it's tempting to assume the two largest-magnitude roots, −5 and 7, give
the max product, but −5×7=−35 is actually the *minimum* — always check
all four sign combinations, don't eyeball it.)

**8. Answer: 19/66.** Total chips = 12, total ways to draw 2 = C(12,2) =
66. Same-color pairs: red C(4,2)=6, blue C(3,2)=3, green C(5,2)=10. Total
favorable = 6+3+10 = 19. Probability = 19/66.

**9. Answer: 10%.** Take French or Spanish (or both) = 65+45−20 = 90%.
Neither = 100−90 = **10%**.

**10. Answer: 16π.** Square area = 64 → side = 8. The inscribed circle's
diameter equals the square's side, so diameter = 8, radius = 4. Area =
πr² = π(4²) = **16π**.

**11. Answer: 15 boys.** Let boys = 5k, girls = 4k. After 6 girls join:
5k/(4k+6) = 5/6 → 30k = 5(4k+6) → 30k = 20k+30 → 10k=30 → k=3. Boys =
5k = **15**. Check: girls = 4(3)+6 = 18, ratio 15:18 = 5:6 ✓.

**12. Answer: 33.** a₁=3. a₂=2(3)−1=5. a₃=2(5)−1=9. a₄=2(9)−1=17.
a₅=2(17)−1=**33**.

### Habit to keep

Questions 5 and 7 above both have a specific trap built in (stopping one
step early on a rate problem; eyeballing which sign combination maximizes
a product instead of checking all four). Neither trap is a knowledge gap
— they're exactly the kind of shortcut your brain takes under time
pressure. The fix is a specific, repeatable check, not "be more careful":
after solving, substitute your answer back into the original condition
and confirm it holds numerically, every single time, even on questions
that feel easy.

### Scoring
10–12/12 = Q165+ pace · 8–9 = Q160–164 · below 8: this set is
combinatorics- and arithmetic-heavy — if your misses cluster on
counting problems (4, 8) specifically, drill "choose vs. arrange" framing
explicitly before your next session, since that distinction (not the
formula itself) is usually the actual gap.
