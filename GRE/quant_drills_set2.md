# GRE Quant — Drill Set 2 (Harder)

**Timer: 1:30/question — 12 questions in 18 minutes flat, no exceptions.**
This set drops the "easy warm-up" questions from Set 1 and goes straight
to the trap-dense territory of a 165+ scorer: exponent rules under
disguise, combinatorics, and data interpretation where the trap is in
what the chart does *not* tell you.

Do not start this set until you scored 11–12/12 on `quant_drills.md`. If
you scored below that, repeat Set 1 until you do — adding difficulty on
top of unfixed gaps just compounds the gaps.

## Quantitative Comparison

**1.** x and y are positive integers and x^y = y^x, with x ≠ y.

Quantity A: x
Quantity B: y

**2.** Set T consists of all integers from 1 to 100, inclusive.

Quantity A: The number of integers in T divisible by 6
Quantity B: The number of integers in T divisible by 4 but not by 8

## Problem Solving

**3.** A committee of 4 people is to be chosen from 6 men and 5 women.
How many committees are possible that include at least 1 woman?

**4.** If (2^a)(2^b) = 2^12 and a − b = 2, what is the value of a?

**5.** A bag contains only nickels, dimes, and quarters worth $6.25 in
total. There are twice as many dimes as nickels, and the number of
quarters is 5 less than the number of dimes. How many dimes are in the bag?

**6.** The figure (not shown) is a right triangle with legs 9 and 12. A
circle is inscribed in the triangle, tangent to all three sides. What is
the radius of the inscribed circle?

**7.** A factory's defect rate is 2% per unit, and defects occur
independently. Of the next 3 units produced, what is the probability
that exactly 1 is defective? (Express as a decimal, nearest thousandth.)

**8.** The table below shows the number of applicants and admits at
College X by department.

| Department | Applicants | Admitted |
|---|---|---|
| Engineering | 400 | 80 |
| Arts | 600 | 180 |

Quantity A: The overall admit rate across both departments combined
Quantity B: The simple average of the two departments' individual admit rates

Is Quantity A greater, less than, equal to, or is the relationship
indeterminate? (This is Simpson's-paradox territory — answer before
reading the solution.)

**9.** If x² − 6x + k = 0 has exactly one solution, what is the value of k?

**10.** A rectangular garden is to be enclosed by fencing on three sides
(the fourth side is an existing wall) using exactly 60 meters of fence.
What is the maximum possible area of the garden, in square meters?

**11.** Of the students at a school, 60% take French, 45% take Spanish,
and 20% take both. What percent of students take neither?

**12.** A sequence is defined by a₁ = 3 and aₙ = 2aₙ₋₁ − 1 for n > 1. What
is a₅?

---

## Worked Solutions

**1. Answer: (D)? No — (A) or (B) cannot both be determined, but check
the specific integer constraint.** The only positive integers x ≠ y with
x^y = y^x are x=2, y=4 (2^4=16=4^2) and its reverse x=4, y=2. Since the
problem doesn't fix which is x and which is y, both (A) and (B) are
achievable depending on the assignment. **Answer: (D).** (Trap: most
test-takers don't know 2^4 = 4^2 is essentially the *only* non-trivial
integer solution to this equation — memorize it, it recurs.)

**2. Answer: (A).** Divisible by 6 in 1–100: ⌊100/6⌋ = 16. Divisible by 4
but not 8: divisible by 4 gives ⌊100/4⌋ = 25; divisible by 8 gives
⌊100/8⌋ = 12; so divisible by 4 but not 8 = 25 − 12 = 13. 16 > 13, so A > B.

**3. Answer: 315.** Total committees of 4 from 11 people: C(11,4) =
11·10·9·8/24 = 330. Subtract all-male committees (0 women): C(6,4) =
C(6,2) = 15. At-least-1-woman = 330 − 15 = **315**. (Trap: "at least 1"
problems are almost always faster solved as total minus the complement —
trying to sum the 1-woman, 2-women, 3-women, and 4-women cases directly
works but costs you three extra minutes you don't have.)

**4. Answer: a = 7.** (2^a)(2^b) = 2^(a+b) = 2^12, so a+b = 12. With
a−b = 2: adding the equations, 2a = 14, a = 7.

**5. Answer: 20 dimes.** Let nickels = n, dimes = 2n, quarters = 2n−5.
Work in cents to avoid decimal slips: 5n + 10(2n) + 25(2n−5) = 625 →
5n + 20n + 50n − 125 = 625 → 75n = 750 → n = 10. Dimes = 2n = **20**.
Check: nickels=10 (50¢), dimes=20 ($2.00), quarters=15 ($3.75); total =
0.50+2.00+3.75 = $6.25 ✓. (Habit to keep: if your algebra ever produces a
non-integer for a quantity the problem implies must be whole — a count of
coins, people, or units — that's your signal to recheck your equation
setup before blaming arithmetic, not a sign to round and move on.)

**6. Answer: 3.** Right triangle legs 9, 12, hypotenuse = 15 (9-12-15 is
a 3-4-5 triple ×3). Inscribed circle radius formula for a right triangle:
r = (leg1 + leg2 − hypotenuse)/2 = (9+12−15)/2 = 6/2 = 3.

**7. Answer: 0.058.** Binomial: C(3,1)(0.02)¹(0.98)² = 3 × 0.02 × 0.9604
= 0.0576576 ≈ **0.058**.

**8. Answer: (B) is greater — classic Simpson's-paradox setup, but check
the actual numbers.** Engineering admit rate = 80/400 = 20%. Arts admit
rate = 180/600 = 30%. Simple average of the two rates = (20+30)/2 = 25%.
Overall combined rate = (80+180)/(400+600) = 260/1000 = 26%. **Overall
(26%) is actually greater than the simple average (25%) here** — Quantity
A > Quantity B. (The lesson: Simpson's paradox requires the group sizes
to interact with the rates in a specific way; don't assume it applies
just because group sizes differ — compute both quantities explicitly
every time.)

**9. Answer: k = 9.** Exactly one solution means the discriminant is 0:
b² − 4ac = 0 → 36 − 4k = 0 → k = 9. (Confirms (x−3)² = 0.)

**10. Answer: 450 square meters.** Let the two equal sides (perpendicular
to the wall) be x, and the side parallel to the wall be y. Fence used:
2x + y = 60 → y = 60−2x. Area = xy = x(60−2x) = 60x − 2x². Maximize via
vertex of downward parabola: x = −60/(2×−2) = 15. Area = 15×(60−30) =
15×30 = **450**.

**11. Answer: 15%.** Take French or Spanish (or both) = 60+45−20 = 85%.
Neither = 100−85 = **15%**.

**12. Answer: a₅ = 35.** a₁=3, a₂=2(3)−1=5, a₃=2(5)−1=9, a₄=2(9)−1=17,
a₅=2(17)−1=**35**.

### Scoring and the honest part of this drill

If you got question 5 "wrong" by not noticing the non-integer result,
that's not a loss — recognizing a modeling dead-end under time pressure
and re-reading rather than brute-forcing a wrong decimal answer is
exactly the skill this set is testing. Log which questions you missed
and *why* (careless arithmetic vs. didn't know the inscribed-circle
formula vs. didn't recheck a non-integer result) in `PROGRESS_LOG.md`.

10–12/12 = comfortably Q165+ pace on hard material. 7–9 = solid but you
have specific gaps — identify them by topic, not by "I need more
practice." Below 7 = go back to `quant_drills.md` Set 1 and re-earn the
prerequisite before returning here.
