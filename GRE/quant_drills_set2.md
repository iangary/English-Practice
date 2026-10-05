# GRE Quant — Drill Set 2 (Harder, Tighter Clock)

**Prerequisite:** Score 9+/12 on `quant_drills.md` (Set 1) before starting
this set. If you haven't, redo Set 1 instead — more volume at a level
you haven't stabilized just trains the wrong reflexes faster.

**Timer: 1:30/question average — for this set of 12, give yourself 18
minutes total, no scratch calculator beyond basic arithmetic.** That's
15 seconds tighter per question than Set 1. The real test doesn't get
easier because you're tired in section 2; this set trains you to hold
pace when the margin for re-reading shrinks.

## Quantitative Comparison

**1.** x and y are integers such that x > y > 0 and x² − y² = 45.

Quantity A: x − y
Quantity B: 5

**2.** Set S = {2, 4, 8, 16, 32, ...} (each term is double the previous,
starting at 2). Set T contains the first 6 terms of S.

Quantity A: The median of T
Quantity B: The mean of T

**3.** A rectangle has perimeter 28 and area 48.

Quantity A: The length of the longer side
Quantity B: 9

## Problem Solving

**4.** A mixture is 40% acid and 60% water by volume. How many liters of
pure acid must be added to 10 liters of this mixture to make a new
mixture that is 60% acid?

**5.** Working alone, Pump A can fill a tank in 6 hours; Pump B can fill
the same tank in 4 hours. If Pump A works alone for 2 hours before Pump
B joins it, how much additional time (in hours) is needed, with both
pumps working together, to finish filling the tank?

**6.** A number is chosen at random from the integers 1 through 100
inclusive. What is the probability that the number is divisible by
either 4 or 6 (or both)?

**7.** In a class of 30 students, the ratio of students who play only
chess to only soccer to both to neither is 3:4:2:1. How many students
play chess (whether or not they also play soccer)?

**8.** The volume of a cube is numerically equal to its surface area.
What is the length of one edge of the cube?

**9.** If the sum of 5 consecutive even integers is 150, what is the
product of the smallest and largest of the five?

**10.** A function is defined as f(x) = x² − 3x + 2 for all real x. For
how many integer values of x between −5 and 5, inclusive, is f(x) ≤ 0?

**11.** An investment grows at 20% per year for two years, then
declines by 20% in the third year. What is the overall percent change
over the three years, to the nearest whole percent?

**12.** Data set D has a standard deviation of 0. If one value, 12, is
known to be in the set, and the set has 7 members, what is the sum of
all 7 members?

---

## Worked Solutions

**1. Answer: (D).** x² − y² = (x−y)(x+y) = 45. Since x and y are
integers with x > y > 0, (x−y) and (x+y) are both positive integers
whose product is 45, and (x+y) > (x−y). Factor pairs of 45: (1,45),
(3,15), (5,9). Each gives a different value for x−y (1, 3, or 5), so
the relationship cannot be determined — Quantity A could be less than,
equal to, or greater than 5 depending on which factor pair applies.
(Trap: assuming there's only one valid (x,y) pair just because the
equation looks fully determined.)

**2. Answer: (B).** T = {2,4,8,16,32,64}. Median = (8+16)/2 = 12. Sum =
2+4+8+16+32+64 = 126, mean = 126/6 = 21. Mean > median, since the
distribution is heavily skewed by the large final terms. B is greater.

**3. Answer: (B).** Let sides be L and W. 2(L+W)=28 → L+W=14. LW=48.
Solving: L and W are roots of t² − 14t + 48 = 0 → (t−6)(t−8)=0 → sides
are 6 and 8. The longer side is 8, which is less than 9, so Quantity B
is greater. (Trap: it's tempting to stop once you've solved for the
sides and forget to actually compare 8 to 9 — finish the comparison,
not just the algebra.)

**4. Answer: 5 liters.** Acid in original mixture = 0.40 × 10 = 4 L.
Water = 6 L (unchanged by adding acid). Let x = liters of pure acid
added. New total volume = 10 + x, new acid = 4 + x. Set (4+x)/(10+x) =
0.60 → 4 + x = 6 + 0.6x → 0.4x = 2 → x = 5.

**5. Answer: 8/5 hours (1.6 hours).** Pump A's rate = 1/6 tank/hr, Pump
B's rate = 1/4 tank/hr. In the first 2 hours, A alone fills 2×(1/6) =
1/3 of the tank. Remaining = 2/3. Combined rate once both work = 1/6 +
1/4 = 5/12 tank/hr. Time to finish the remaining 2/3 = (2/3) ÷ (5/12) =
(2/3) × (12/5) = 24/15 = 8/5 = 1.6 hours.

**6. Answer: 33/100.** Multiples of 4 from 1–100: 25 (4,8,...,100).
Multiples of 6: 16 (6,12,...,96). Multiples of both 4 and 6 (i.e., of
12): 8 (12,24,...,96). By inclusion-exclusion: 25 + 16 − 8 = 33.
Probability = 33/100. (Trap: forgetting to subtract the overlap —
without it you'd wrongly get 41/100.)

**7. Answer: 15 students.** Ratio parts: only chess (3), only soccer
(4), both (2), neither (1); total parts = 10, representing 30 students,
so each part = 3 students. Chess players (only chess + both) = (3+2)
parts = 5 parts = 15 students.

**8. Answer: 6.** Volume = s³, surface area = 6s². Setting s³ = 6s² →
s = 6 (dividing both sides by s², valid since s ≠ 0).

**9. Answer: 884.** Let the five consecutive even integers be
n−4, n−2, n, n+2, n+4 (centered on n). Their sum = 5n = 150 → n = 30.
The integers are 26, 28, 30, 32, 34. Smallest × largest = 26 × 34 =
884.

**10. Answer: 2 integer values.** f(x) = x² − 3x + 2 = (x−1)(x−2).
This is ≤ 0 when x is between the roots inclusive, i.e., 1 ≤ x ≤ 2.
Integers in that range: just 1 and 2. (Trap: the "−5 to 5" range in the
question is a red herring meant to make you count a wider span than the
inequality actually allows — the binding constraint comes from the
inequality, not the stated bounds.)

**11. Answer: approximately 15% increase.** Growth factor =
1.20 × 1.20 × 0.80 = 1.152. That's a 15.2% increase overall, rounding
to 15%. (Trap: a 20% gain + 20% gain − 20% loss does NOT net to a 20%
gain; multiply the factors, never add/subtract the percentages
directly.)

**12. Answer: 84.** Standard deviation of 0 means every value in the
set is identical. Since 12 is in the set, all 7 members equal 12. Sum =
7 × 12 = 84.

### Habit to keep

Several of the traps above (3, 6, 9, 10) are built the same way: the
method is short, but the last step — comparing to the right quantity,
subtracting the overlap, finishing the multiplication, checking which
constraint actually binds — is where the point is won or lost. Build
the habit of doing that last step explicitly and out loud, every time,
especially when you feel confident. Confidence is exactly when it gets
skipped.

### Scoring
11–12/12 in 18 minutes = Q167+ pace · 9–10 = Q162–166 · below 9 or over
time: don't advance to a Set 3 — instead redo Set 1 and Set 2 missed
questions from scratch (not from memory) in 48 hours, and log in
`PROGRESS_LOG.md` whether the miss was timing or concept each time.
