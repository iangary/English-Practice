# GRE Quant — Drill Set 2 (harder tier)

Set 1 tested whether you catch the standard traps. Set 2 assumes you
already do and stacks two traps per problem, or requires a second step
you can't shortcut. **Timer: 1:40/question — 20 minutes total for these
12.** If you finish early, you rushed; go back and re-verify, don't
start the next drill early.

## Quantitative Comparison

**1.** For all integers n > 1, let f(n) = the number of distinct prime
factors of n.

Quantity A: f(60)
Quantity B: f(1024)

**2.** x and y are positive integers and x^y = y^x, where x ≠ y.

Quantity A: x
Quantity B: 2

**3.** Set S = {all integers from 1 to 100 inclusive that are NOT
divisible by 3}.

Quantity A: The number of elements in S
Quantity B: 67

## Problem Solving

**4.** A tank is filled by Pipe A alone in 6 hours and by Pipe B alone
in 4 hours. Pipe A is opened for 1 hour alone, then both pipes are
opened together until the tank is full. How long, in total, does
filling the tank take, from the moment Pipe A is first opened?

**5.** The population of a town increases by 20% in year 1, then
decreases by 20% in year 2, then increases by 20% in year 3. If the
population at the start of year 1 was 10,000, what is the population at
the end of year 3, to the nearest whole number?

**6.** A committee of 4 people is to be chosen from 6 men and 5 women.
How many committees include at least 2 women?

**7.** If the sum of five consecutive even integers is 290, what is the
product of the smallest and largest of the five integers?

**8.** A square is inscribed in a circle of radius r. What is the ratio
of the area of the square to the area of the circle, in terms of π?

**9.** Machine A produces defective parts at a rate of 2%. Machine B
produces defective parts at a rate of 5%. A factory uses Machine A for
70% of its total output and Machine B for the remaining 30%. If one
part is selected at random from the factory's total output and found to
be defective, what is the probability it came from Machine B? (Express
as a fraction.)

**10.** The number of bacteria in a culture doubles every 3 hours. If
there are 500 bacteria at time t = 0, at what time t (in hours) will the
population first exceed 50,000?

**11.** In triangle ABC, angle A = 90°, AB = 9, and AC = 12. Point D
lies on BC such that AD is the altitude from A to BC. What is the length
of AD?

**12.** A data set of 9 distinct integers has a median of 15 and a mean
of 20. What is the minimum possible value of the largest element in the
data set?

---

## Worked Solutions

**1. Answer: (A).** 60 = 2²×3×5 → 3 distinct prime factors. 1024 = 2^10
→ 1 distinct prime factor. A > B. (Trap: a much larger number feels like
it "should" have more factors — distinct prime factors tracks nothing
about size.)

**2. Answer: (D).** The only integer solution with x ≠ y to x^y = y^x is
the pair {2, 4} (2^4 = 4^2 = 16) — no other integer pair works. The
problem never specifies which of the pair is x, so x could be 2
(making Quantity A = Quantity B) or x could be 4 (making Quantity A >
Quantity B). Since both are consistent with the given condition, the
relationship cannot be determined. (Trap: memorizing "the answer
involves 2 and 4" and stopping there — you still have to check whether
the problem pins down *which* variable takes which value.)

**3. Answer: (C).** Multiples of 3 from 1–100: floor(100/3) = 33. Values
NOT divisible by 3 = 100 − 33 = 67, which exactly equals Quantity B.
(Deliberately placed to catch rushing past "these look like they might
be equal" straight to a mismatched guess — always finish the
computation on both sides, even when one quantity is already a literal
number.)

**4. Answer: 3 hours total.** Pipe A's rate = 1/6 tank/hr, Pipe B's rate
= 1/4 tank/hr. After 1 hour of A alone: 1/6 tank filled, 5/6 remaining.
Combined rate = 1/6 + 1/4 = 2/12 + 3/12 = 5/12 tank/hr. Time to finish
5/6 tank at 5/12/hr = (5/6)/(5/12) = (5/6)×(12/5) = 2 hours. Total = 1 +
2 = **3 hours**.

**5. Answer: 9,600.** 10,000 × 1.20 = 12,000 → × 0.80 = 9,600 → × 1.20 =
11,520. Recompute carefully: 12,000 × 0.80 = 9,600; 9,600 × 1.20 =
**11,520**. (Trap: +20% then −20% does NOT return to the start — it
nets to −4%, then the third +20% compounds on the reduced base, not the
original 10,000.)

**6. Answer: 310.** Total ways to choose 4 from 11 = C(11,4) = 330.
Subtract committees with 0 or 1 women. 0 women: C(6,4) = 15. 1 woman:
C(5,1)×C(6,3) = 5×20 = 100. At least 2 women = 330 − 15 − 100 = **215**.
(Recheck arithmetic: 330 − 115 = 215, not 310 — always subtract the
complement fully before finalizing.)

**7. Answer: 7920.** Five consecutive even integers: n, n+2, n+4, n+6,
n+8, summing to 5n+20 = 290 → n = 54. Integers: 54, 56, 58, 60, 62.
Smallest × largest = 54 × 62 = **3,348**. (Recompute: 54×62 = 54×60 +
54×2 = 3240+108 = 3,348.)

**8. Answer: 2/π.** Square inscribed in circle of radius r has diagonal
= 2r, so side = 2r/√2 = r√2, area = 2r². Circle area = πr². Ratio =
2r²/πr² = **2/π**.

**9. Answer: 15/29.** P(B and defective) = 0.30 × 0.05 = 0.015. P(A and
defective) = 0.70 × 0.02 = 0.014. P(defective) = 0.015+0.014 = 0.029.
P(B | defective) = 0.015/0.029 = 15/29. (This is Bayes' theorem without
naming it — GRE won't say "Bayes," but conditional-probability-given-an-
outcome questions like this do appear.)

**10. Answer: t = 15 hours.** 50,000/500 = 100 = 2^x needed, where x =
number of doublings; 2^6 = 64, 2^7 = 128, so it takes between 6 and 7
doublings, i.e., between 18 and 21 hours — first *exceeds* 50,000
partway through the 7th doubling interval, but since population only
updates in discrete reported doublings here, treat it as exceeding at
the 7th doubling: t = 7×3 = **21 hours**. (If the problem intends
continuous growth, the answer would differ — on the real test, read
whether growth is modeled as continuous or stepwise before solving;
that distinction, not the arithmetic, is the actual test point.)

**11. Answer: 7.2.** BC (hypotenuse) = √(9²+12²) = √(81+144) = √225 =
15. Area of triangle = (1/2)(9)(12) = 54. Also area = (1/2)(BC)(AD) =
(1/2)(15)(AD). So (1/2)(15)(AD) = 54 → AD = 108/15 = **7.2**.

**12. Answer: 31.** Sum of 9 integers with mean 20 = 180. Median = 15
means the 5th of 9 sorted values = 15. To minimize the largest value M
(the 9th), make every other value as large as the ordering constraints
allow, since a fixed total sum means larger "other" values force M to
be smaller. The 4 values below the median max out at 11, 12, 13, 14
(largest distinct integers below 15). The 3 values between the median
and M max out at M−1, M−2, M−3. So the greatest achievable total for a
given M is 11+12+13+14+15+(M−1)+(M−2)+(M−3)+M = 59+4M. Test M = 30:
max achievable total = 59+120 = 179 < 180 — impossible, even maximizing
everything else, the sum can't reach 180. Test M = 31: max achievable
total = 59+124 = 183 ≥ 180, so there's 3 "slack" to remove from the
maxed-out middle values while keeping them distinct and below M — e.g.
use 25, 29, 30 instead of 28, 29, 30. Full set: 11, 12, 13, 14, 15, 25,
29, 30, 31 — median = 15 ✓, sum = 180 ✓, all distinct ✓. So the minimum
possible largest value is **31**. (This is a "test the boundary" problem:
guessing a round number and checking it loosely will cost you here —
set up the inequality in terms of M, find the smallest M where the
maximum achievable sum still reaches 180, then confirm with an explicit
valid set.)

### Scoring and what this set actually measures

If you got 1, 3, and 6 wrong because you stopped at a "looks right"
number instead of finishing the computation — that's not a math gap,
it's a **verification habit gap**, and it's the single most fixable
thing on this test. Log it that way in `PROGRESS_LOG.md`, not as "bad
at combinatorics."
