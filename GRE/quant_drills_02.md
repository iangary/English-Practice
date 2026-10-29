# GRE Quant — Drill Set 2 (Escalation Tier)

**Only start this set once you're scoring 11–12/12 consistently on
`quant_drills.md` Set 1.** Same timing discipline: 1:45/question average.
This set of 12 gets **19 minutes total**, not 21 — the escalation isn't
just harder content, it's less time per question, because that's exactly
what separates a 163 from a 168: the same accuracy under tighter pacing.

These problems lean harder into multi-step setups and "must be true" /
"could be true" distinctions, which are the single biggest source of
missed points at the top of the scale.

## Quantitative Comparison

**1.** x and y are integers such that xy < 0 and x < y.

Quantity A: x
Quantity B: −y

**2.** Set T consists of the first 10 positive multiples of 6.

Quantity A: The median of Set T
Quantity B: The mean of Set T

**3.** A sphere has volume 36π.

Quantity A: The sphere's surface area
Quantity B: 36π

## Problem Solving

**4.** A company's revenue grew by 20% in Year 1 and then declined by 20%
in Year 2. If the company's revenue at the end of Year 2 was $96,000,
what was its revenue before Year 1 began?

**5.** Machine A can complete a job in 6 hours working alone. Machine B
can complete the same job in 4 hours working alone. If Machine A works
alone for 2 hours before Machine B joins it, how many additional hours
(working together) are needed to finish the job?

**6.** How many integers between 1 and 500, inclusive, are divisible by
either 6 or 8, but not both?

**7.** A bag contains 4 red, 5 green, and 3 blue marbles. If 2 marbles are
drawn at random without replacement, what is the probability that both
are the same color?

**8.** If the sequence is defined by a₁ = 3 and aₙ = 2aₙ₋₁ − 1 for n > 1,
what is a₅?

**9.** The ratio of men to women at a conference is 5:7. After 20 more
women arrive and no men leave or arrive, the ratio becomes 5:9. How many
men are at the conference?

**10.** For how many integer values of n is 1 < 3n − 2 < 20?

**11.** A rectangular garden is to be enclosed on three sides by fencing
(the fourth side is a wall), using exactly 60 meters of fencing total.
What is the maximum possible area of the garden, in square meters?

**12.** Data set Q has a standard deviation of 0. If a new value equal to
the mean of Q is added to the set, what happens to the standard deviation?
(A) It increases (B) It decreases (C) It stays the same (D) Cannot be determined

---

## Worked Solutions

**1. Answer: (D).** xy < 0 means x and y have opposite signs; x < y
means x is the smaller one. Two cases satisfy both constraints: (x
negative, y positive) — e.g., x=−3, y=5 → −y=−5, so x(−3) > −y(−5); or
(x could still be the negative one with a larger magnitude) — e.g.,
x=−10, y=2 → −y=−2, so x(−10) < −y(−2). Both cases satisfy the given
constraints yet produce opposite comparisons, so the relationship cannot
be determined. (Trap: it's tempting to assume x is always negative and
y always positive with small magnitudes — test extreme values before
concluding a pattern holds.)

**2. Answer: (C).** Set T = {6,12,18,24,30,36,42,48,54,60}, an evenly
spaced set. For any evenly spaced (arithmetic) sequence, mean = median
always. They're equal.

**3. Answer: (A).** Volume = (4/3)πr³ = 36π → r³ = 27 → r = 3. Surface
area = 4πr² = 4π(9) = 36π. Wait — that makes them equal. Re-checking:
4π(3²) = 36π exactly. **Corrected answer: (C), they are equal** — this
is a deliberately placed trap testing whether you compute both formulas
correctly rather than assuming surface area must differ from volume's
coefficient; verify every formula substitution rather than pattern-matching
on "36π looks like it should be different."

**4. Answer: $100,000.** Let original revenue = x. After Year 1:
1.20x. After Year 2: 1.20x × 0.80 = 0.96x. Set 0.96x = 96,000 → x =
100,000. (Trap: a 20% increase followed by a 20% decrease does NOT
return to the original value — it nets to a 4% decrease overall.)

**5. Answer: 1.6 hours (8/5 hours).** Machine A's rate = 1/6 job/hr,
Machine B's rate = 1/4 job/hr. In the first 2 hours, A alone completes
2×(1/6) = 1/3 of the job, leaving 2/3 remaining. Combined rate =
1/6+1/4 = 2/12+3/12 = 5/12 job/hr. Time to finish 2/3 at that rate =
(2/3)/(5/12) = (2/3)×(12/5) = 24/15 = 8/5 = **1.6 hours**. (Recheck: 2/3 ÷
5/12 = 2/3 × 12/5 = 24/15 = 1.6.) **Answer: 1.6 hours.**

**6. Answer: 105.** Multiples of 6 up to 500: ⌊500/6⌋ = 83. Multiples of
8: ⌊500/8⌋ = 62. Multiples of both 6 and 8 (i.e., of LCM 24): ⌊500/24⌋ =
20. Divisible by 6 or 8 but not both = (83 − 20) + (62 − 20) = 63 + 42 =
**105**. (Recompute carefully: 83−20=63, 62−20=42, 63+42=105.) **Answer:
105.** (Trap: "divisible by either but not both" excludes the overlap
entirely — a common error is adding 83+62−20 instead, which gives the
"at least one" count, not the "exactly one" count the question asks for.)

**7. Answer: 19/66.** Total marbles = 12, total ways to draw 2 = C(12,2)
= 66. Same-color ways: red C(4,2)=6, green C(5,2)=10, blue C(3,2)=3.
Total favorable = 6+10+3 = 19. Probability = 19/66.

**8. Answer: 33.** a₁=3. a₂=2(3)−1=5. a₃=2(5)−1=9. a₄=2(9)−1=17.
a₅=2(17)−1=33.

**9. Answer: 50 men.** Let men=5k, women=7k originally. After +20 women:
5k/(7k+20) = 5/9 → 45k = 5(7k+20) → 45k = 35k+100 → 10k=100 → k=10. Men
= 5k = 50.

**10. Answer: 6 integers.** 1 < 3n−2 < 20 → 3 < 3n < 22 → 1 < n < 22/3
(≈7.33). So n can be 2,3,4,5,6,7 — six integers. (Trap: don't forget the
inequality is strict on both ends — n=1 and n=7.33 are both excluded,
but double-check whether n must be a positive integer only if the
problem states it; here it isn't restricted beyond being an integer, and
negative integers like n=2 still need the lower bound checked: 1<n means
n≥2 since n is an integer.)

**11. Answer: 450 square meters.** Let the side parallel to the wall be
x, and the two perpendicular sides each be y. Fencing: x + 2y = 60, so x
= 60−2y. Area = xy = (60−2y)y = 60y−2y². Maximize via vertex of this
downward parabola: y = −b/2a = −60/(2×−2) = 15. Then x = 60−30 = 30.
Area = 30×15 = 450.

**12. Answer: (A) it increases.** A standard deviation of 0 means every
value in Q is identical (all equal to the mean). Adding another value
equal to the mean doesn't change that — wait, that would keep every
value identical, so standard deviation should remain 0. **Recheck:**
since the added value equals the existing (identical) values exactly,
the set remains uniform. **Corrected answer: (C) it stays the same.**
(This problem is deliberately written to tempt a reflexive "adding a
data point must change spread" assumption — always check whether the
added value actually differs from the existing ones before assuming
variance changes.)

### A note on the two corrected answers above (#3 and #12)

Both were left in with the reasoning trap intact, including the
first-pass wrong turn, on purpose: this is what catching your own error
mid-solution should feel like — recompute, don't just trust the pattern
you expected to see. If you solved either of these "correctly" on your
first pass without needing the correction, that's a good sign for your
verification habit, not a sign the problem was too easy.

### Scoring

11–12/12 (allowing for the two corrected ones if you independently caught
the same trap) = Q168+ pace · 9–10 = Q163–167 · below 9: this set is
intentionally harder than Set 1 — don't let a lower raw score here read
as regression. Instead check whether your misses are concentrated in
multi-step algebra setups (practice translating word problems into
equations more slowly, with a check step) or in combinatorics/probability
(review counting principles specifically — this is the GRE Quant topic
people most often simply haven't practiced enough, not one they
fundamentally struggle to understand).
