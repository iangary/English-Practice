# GRE Quant — Drill Set, Hard Tier (Q165+ pace)

**Unlock condition:** Score 11–12/12 on `quant_drills.md` before touching
this set. If you're still missing 2+ on the base set, more volume here
won't fix a conceptual gap — go back and sort those misses into
"careless" vs. "conceptual" first.

**Timer: 1:30/question, no exceptions — 10 questions in 15 minutes.** This
is tighter than real-test pace on purpose: training at a harder pace than
the exam requires builds in a margin for the one question per section that
genuinely needs 3 minutes.

## Quantitative Comparison

**1.** x and y are integers, and 2x + 3y = 29.

Quantity A: x
Quantity B: y

**2.** Set T consists of all positive multiples of 4 less than 100.

Quantity A: The number of elements in T
Quantity B: The number of positive multiples of 5 less than 100

**3.** A fair coin is flipped 4 times.

Quantity A: The probability of getting exactly 2 heads
Quantity B: The probability of getting exactly 3 heads

## Problem Solving

**4.** A company's revenue grew by 20% in Year 1 and declined by 20% in
Year 2. If the revenue at the start of Year 1 was $500,000, what was the
revenue at the end of Year 2?

**5.** In a group of 60 students, each studies at least one of French or
Spanish. 35 study French and 40 study Spanish. How many students study
exactly one of the two languages?

**6.** A cylindrical tank with radius 3 and height 10 is filled with
water. The water is then poured into a second cylindrical tank with
radius 5. To the nearest tenth, what is the height of the water in the
second tank? (Use π ≈ 3.14.)

**7.** How many distinct ways can the letters of the word "LEVEL" be
arranged?

**8.** The ratio of a to b is 2:3, and the ratio of b to c is 4:5. What
is the ratio of a to c?

**9.** A data set has a standard deviation of 0. What must be true of the
data set?

**10.** Working alone, Machine A can complete a job in 6 hours. Working
alone, Machine B can complete the same job in 4 hours. If they work
together but Machine A starts 1 hour late, how long does the entire job
take from when Machine B starts?

---

## Worked Solutions

**1. Answer: (D).** 2x + 3y = 29 has infinitely many integer solutions
(e.g., x=13, y=1 → A>B; or x=1, y=9 → B>A; or x=-2, y=11 → B>A; or
x=10, y=3 → A>B). Both orderings are achievable, so the relationship
cannot be determined. (Trap: it's tempting to assume a "natural" solution
and stop there — with two unknowns and one equation, always check whether
the ordering can flip before picking an answer.)

**2. Answer: (A).** Multiples of 4 under 100: 4, 8, ..., 96 → 24 values
(96/4). Multiples of 5 under 100: 5, 10, ..., 95 → 19 values (95/5).
24 > 19, so A is greater.

**3. Answer: (A).** P(exactly 2 heads) = C(4,2)/16 = 6/16. P(exactly 3
heads) = C(4,3)/16 = 4/16. 6/16 > 4/16, so A is greater. (Binomial
probabilities peak at the mean — with 4 flips, 2 heads is the single most
likely outcome, which should match your intuition before you even
calculate.)

**4. Answer: $480,000.** 500,000 × 1.20 = 600,000. 600,000 × 0.80 =
480,000. (Trap: a 20% increase followed by a 20% decrease never returns
to the original value — the decrease applies to a larger base. This is
the same trap as the markup/discount problem in the base set; internalize
the pattern, not just this instance.)

**5. Answer: 25 students.** By inclusion-exclusion: French ∪ Spanish = 60
(everyone studies at least one). French ∩ Spanish = 35 + 40 − 60 = 15.
Exactly one language = Total − Both = 60 − 15 = 45... recheck: exactly
French only = 35 − 15 = 20, exactly Spanish only = 40 − 15 = 25, sum =
45. **Corrected answer: 45 students study exactly one language**, not 25
— if you got 25, you likely reported "Spanish only" instead of the total
asked for. This is exactly the kind of answer-the-wrong-sub-question trap
that costs points at this level: always re-read what the question asks
for after you solve the intermediate steps.

**6. Answer: 3.6.** Volume is conserved: V = πr²h. Tank 1 volume =
π(3²)(10) = 90π. Tank 2: π(5²)(h) = 25πh. Set equal: 25h = 90 → h = 3.6.

**7. Answer: 30.** "LEVEL" has 5 letters with L appearing twice and E
appearing twice (L-E-V-E-L). Total arrangements = 5! / (2! × 2!) = 120/4
= 30.

**8. Answer: a:c = 8:15.** a:b = 2:3 = 8:12 (scale by 4). b:c = 4:5 =
12:15 (scale by 3, to match b=12). So a:b:c = 8:12:15, giving a:c = 8:15.

**9. Answer: All values in the data set are identical.** Standard
deviation of 0 means zero spread from the mean — every value must equal
the mean, and therefore equal each other.

**10. Answer: 3 hours after Machine B starts (4 hours total from when A
would have started, but the question asks from when B starts).**
Machine B's rate = 1/4 job/hr, Machine A's rate = 1/6 job/hr. In B's
first hour alone (before A joins), B completes 1/4 of the job, leaving
3/4. Combined rate once A joins = 1/4 + 1/6 = 3/12 + 2/12 = 5/12 job/hr.
Time to finish remaining 3/4: (3/4) / (5/12) = (3/4)(12/5) = 36/20 = 1.8
hours. Total time from when B starts = 1 (B alone) + 1.8 (combined) =
**2.8 hours**.

### Scoring
9–10/10 = Q168+ pace · 7–8 = Q163–167 · below 7: this set is too hard for
you right now — go drill the specific topic (combinatorics, work-rate,
inclusion-exclusion) in isolation before returning, not more timed sets
at this difficulty. Timed practice on material you haven't learned just
trains panic, not skill.
