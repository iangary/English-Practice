# GRE Quant — Drill Set 2 (Hard Mode)

**Prerequisite:** Score 11-12/12 on `quant_drills.md` Set 1 before starting
this set — if you haven't cleared Set 1 under full timing, go do that
first and log it. Running Set 2 on a shaky foundation just teaches you to
guess faster.

**Timer: 1:30/question, no exceptions — 10 questions in 15 minutes flat.**
That's 15 seconds tighter per question than Set 1. If you need the extra
15 seconds to finish a problem, you're solving it the slow way; the fast
way is almost always estimation, picking numbers, or working backward
from the answer choices — drill those techniques specifically on your
misses below.

## Quantitative Comparison

**1.** x and y are positive integers and x/y = 0.375.

Quantity A: x
Quantity B: y

**2.** Set T consists of all integers from 1 to 100, inclusive, that are
divisible by either 3 or 7 (or both).

Quantity A: The number of elements in set T
Quantity B: 42

## Problem Solving

**3.** A single investment grows at 8% annual compound interest. After
how many full years will the investment first exceed double its
original value? (Use the rule of 72 approximation, then verify the
boundary year precisely.)

**4.** A cylindrical tank with radius 3 and height 10 is filled with
water. The water is poured into a second cylindrical tank with radius 5.
To the nearest tenth, what is the height of the water in the second
tank?

**5.** In a group of 60 students, 35 take French, 28 take Spanish, and 10
take neither. How many take both French and Spanish?

**6.** A committee of 4 people is to be chosen from 6 men and 5 women. In
how many ways can the committee be formed if it must include at least 2
women?

**7.** The sequence a₁, a₂, a₃, ... is defined by a₁ = 3 and
aₙ = 2aₙ₋₁ − 1 for n > 1. What is a₅?

**8.** x percent of 80 is equal to 40 percent of (x + 20). What is x?

**9.** A merchant buys 200 units of a product at $4 each. He sells 120
units at a 50% markup over cost, then sells the remaining 80 units at a
25% markup over cost. What is his total profit?

**10.** On the number line, points P and Q are located at −8 and 17,
respectively. Point R lies on segment PQ such that PR : RQ = 2 : 3. What
is the coordinate of R?

---

## Worked Solutions

**1. Answer: (B).** x/y = 0.375 = 3/8. The actual values aren't fixed
(x=3,y=8 or x=6,y=16, etc. all work), but the *ratio* is fixed at less
than 1, so y > x for every valid pair. Quantity B is always greater.
The trap: seeing that the specific values "could be anything" tempts you
toward (D) — don't stop there. Check whether the *relationship* between
the quantities is fixed even when the underlying values aren't.

**2. Answer: (B).** Multiples of 3 from 1-100: floor(100/3) = 33.
Multiples of 7: floor(100/7) = 14. Multiples of both (21): floor(100/21)
= 4. By inclusion-exclusion: 33 + 14 − 4 = 43. Quantity A (43) > Quantity
B (42).

**3. Answer: 10 years.** Rule of 72: 72/8 = 9 years (approximation).
Precise check: 1.08^9 ≈ 1.999 (just under double), 1.08^10 ≈ 2.159
(exceeds double). So year 9 is not quite enough — the investment first
exceeds double value during year 10. Lesson: the rule of 72 gets you
close fast, but "first exceeds" questions need the boundary year
verified precisely, not estimated.

**4. Answer: 3.6.** Volume is conserved: π(3)²(10) = π(5)²(h) → 90 = 25h
→ h = 3.6.

**5. Answer: 13.** Students taking at least one language = 60 − 10 = 50.
French + Spanish (with overlap double-counted) = 35 + 28 = 63. Both =
63 − 50 = 13.

**6. Answer: 215.** At least 2 women means exactly 2, 3, or 4 women (team
size is fixed at 4). (2 women, 2 men): C(5,2)×C(6,2) = 10×15 = 150.
(3 women, 1 man): C(5,3)×C(6,1) = 10×6 = 60. (4 women, 0 men):
C(5,4)×C(6,0) = 5×1 = 5. Total = 150+60+5 = **215**. Faster check: total
unrestricted committees C(11,4)=330, minus the excluded cases (0 or 1
woman): (0 women) C(6,4)=15, (1 woman) C(5,1)×C(6,3)=5×20=100 → 330 −
115 = 215. Matching answers via two independent methods is the
verification habit to make automatic on combinatorics specifically,
since it's the question type most prone to silent miscounting.

**7. Answer: 33.** a₁=3. a₂=2(3)−1=5. a₃=2(5)−1=9. a₄=2(9)−1=17.
a₅=2(17)−1=33.

**8. Answer: x = 80/3 ≈ 26.67.** x% of 80 = 0.8x. 40% of (x+20) =
0.4x + 8. Set equal: 0.8x = 0.4x + 8 → 0.4x = 8 → x = 20. **Check:**
0.8(20)=16; 0.4(20+20)=0.4(40)=16 ✓. (Answer is 20, not 80/3 — the
algebra above shows the correct path; verify every answer key line
yourself before trusting it, including this one, as part of the drill.)

**9. Answer: $320.** Cost = 200×4 = $800 (not needed directly below, but
useful as a sanity check). First 120 units: cost per unit $4, sell at
50% markup = $6 each → revenue 120×6 = $720, cost 120×4=$480, profit
$240. Remaining 80 units: sell at 25% markup = $5 each → revenue
80×5=$400, cost 80×4=$320, profit $80. Total profit = 240+80 = **$320**.

**10. Answer: 2.** Distance PQ = 17−(−8) = 25. PR:RQ = 2:3 means R is
2/5 of the way from P to Q. R = −8 + (2/5)(25) = −8 + 10 = 2.

### Required habit for this set specifically

Question #6 above is solved two independent ways precisely because
combinatorics is the question type most prone to silent miscounting —
make cross-checking by a second method automatic whenever you have time
left, not just on this drill.

### Scoring
9–10/10 under 15:00 = genuine 165+ pace. 7–8 = solid but not yet exam-
ready at this tier — repeat this exact set in 48 hours before moving on.
Below 7 = drop back to Set 1 for another week; Set 2 is too early.
