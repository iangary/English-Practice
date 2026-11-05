# GRE Quant — Drill Set 2 (harder, tighter clock)

**Timer: 1:30/question average, not 1:45 — 18 minutes total for this set
of 12. This is below real test pace on purpose. If you can hold accuracy
here, real test pacing will feel comfortable; if accuracy collapses,
you've been relying on time you won't have.**

No calculator beyond basic arithmetic. Read every problem twice before
calculating — these are written with at least one deliberate trap each.

## Quantitative Comparison

**1.** x and y are integers such that xy = 36 and x > y > 0.

Quantity A: The smallest possible value of x + y
Quantity B: 13

**2.** Set T = {2, 4, 6, 8, 10}. A number is chosen at random from T, then
a second, different number is chosen at random from the remaining values.

Quantity A: The probability that both numbers chosen are even
Quantity B: 1

**3.** A square and a circle have equal area.

Quantity A: The perimeter of the square
Quantity B: The circumference of the circle

## Problem Solving

**4.** A company's revenue grew by 20% in Year 1 and declined by 20% in
Year 2. If the Year 0 revenue was $500,000, what was the revenue at the
end of Year 2?

**5.** Working alone, Pump A can fill a tank in 6 hours. Working alone,
Pump B can fill the same tank in 4 hours. If both pumps work together but
Pump A starts 1 hour after Pump B, how many total hours does Pump B run
until the tank is full?

**6.** The ratio of men to women at a conference is 5:7. After 20 more
women register and no men register, the ratio becomes 5:9. How many men
are at the conference?

**7.** A sequence is defined by a₁ = 3 and aₙ = 2aₙ₋₁ − 1 for n > 1. What
is a₅?

**8.** In a group of 150 students, every student takes at least one of
French or Spanish. 95 take French and 80 take Spanish. How many take
exactly one of the two languages?

**9.** A box contains 4 red, 3 blue, and 5 green marbles. Two marbles are
drawn at random without replacement. What is the probability that both
are the same color?

**10.** A right circular cylinder has a volume of 150π and a height of 6.
What is the radius of the cylinder's base?

**11.** If |2x − 5| = 9, what is the sum of all possible values of x?

**12.** List L consists of 7 integers with a median of 10 and a mean of
12. If the largest number in the list is removed, the mean of the
remaining 6 numbers is 11. What was the largest number in the original
list?

---

## Worked Solutions

**1. Answer: (C).** xy = 36 with x > y > 0, both integers: possible pairs
(x,y) are (36,1), (18,2), (12,3), (9,4) — (6,6) is excluded since x > y
strictly. Sums: 37, 20, 15, 13. The minimum possible value of x + y is
13, achieved at (9,4). Quantity A (the smallest possible value of x + y)
is therefore exactly 13, equal to Quantity B. **Quantities are equal →
Answer: (C).** (Trap: "smallest possible value of x + y" is itself a
fixed number once you work it out — don't confuse a quantity defined by
a superlative with something inherently variable.)

**2. Answer: (C).** Every member of T = {2, 4, 6, 8, 10} is even, so any
two numbers drawn from T are guaranteed to both be even regardless of
order. Quantity A = 1 = Quantity B. **Quantities are equal → Answer:
(C).** (Trap: skimming "a number is chosen... then a second number" and
assuming a probability calculation is needed, without first checking
whether the set already guarantees the outcome.)

**3. Answer: (A).** Let the square have side s (area = s², perimeter =
4s) and the circle have radius r (area = πr²). Equal areas: s² = πr², so
s = r√π. Perimeter of square = 4s = 4r√π ≈ 7.09r. Circumference of circle
= 2πr ≈ 6.28r. The square's perimeter is larger. **Quantity A is
greater → Answer: (A).** (This follows the isoperimetric principle: among
shapes of equal area, the circle always has the smallest perimeter — a
fact worth memorizing outright rather than re-deriving under time
pressure.)

**4. Answer: $480,000.** Year 1: 500,000 × 1.20 = 600,000. Year 2:
600,000 × 0.80 = 480,000. (Trap: a 20% increase then a 20% decrease does
NOT return to the original value — multiply the factors, 1.20 × 0.80 =
0.96, a net 4% decrease.)

**5. Answer: 2.8 hours.** Pump B's rate = 1/4 tank/hr, Pump A's rate =
1/6 tank/hr. B works alone for the first hour: fills 1/4 of the tank,
leaving 3/4. Then both work together at a combined rate of 1/4 + 1/6 =
5/12 tank/hr. Time to finish the remaining 3/4: (3/4) ÷ (5/12) = (3/4) ×
(12/5) = 36/20 = 1.8 hours. Total time B runs = 1 hour (alone) + 1.8
hours (together) = **2.8 hours.**

**6. Answer: 50 men.** Let men = 5k, women = 7k. After adding 20 women:
5k/(7k+20) = 5/9 → 45k = 35k + 100 → 10k = 100 → k = 10. Men = 5(10) = 50.
Check: women = 7(10)+20 = 90, ratio 50:90 = 5:9 ✓.

**7. Answer: 33.** a₁=3. a₂=2(3)−1=5. a₃=2(5)−1=9. a₄=2(9)−1=17.
a₅=2(17)−1=33.

**8. Answer: 125 students.** Since every student takes at least one
language, the overlap (both) = French + Spanish − Total = 95 + 80 − 150
= 25. French only = 95 − 25 = 70. Spanish only = 80 − 25 = 55. Exactly
one language = 70 + 55 = **125.** (Trap: it's easy to stop at "French
only = 70" and submit that as the answer to a question that actually
asked for *exactly one* language, meaning both groups combined — always
re-read the question stem after finishing the calculation, not just
before starting it.)

**9. Answer: 19/66.** Total marbles = 12, total ways to draw 2 = C(12,2)
= 66. Same-color ways: red C(4,2)=6, blue C(3,2)=3, green C(5,2)=10.
Total same-color = 6+3+10 = 19. Probability = 19/66.

**10. Answer: 5.** Volume = πr²h → 150π = πr²(6) → r² = 25 → r = 5.

**11. Answer: 5.** |2x−5|=9 means 2x−5=9 or 2x−5=−9. First: 2x=14, x=7.
Second: 2x=−4, x=−2. Sum = 7+(−2) = 5.

**12. Answer: 18.** Sum of original 7 numbers = 7×12 = 84. Sum of the
remaining 6 (after removing the largest) = 6×11 = 66. The removed number
= 84 − 66 = **18.** (Note: the median of 10 is extra, unused information
here — GRE Data Analysis questions routinely include a true but
unnecessary fact specifically to test whether you can identify which
given values actually drive the calculation.)

### Scoring
10–12/12 at 1:30/question pace = comfortably on track for Q165+ under
real conditions · 7–9 = on track but log which traps you fell for in
`PROGRESS_LOG.md` · below 7 at this pace: redo this exact set at 1:45/
question before concluding it's a conceptual gap rather than a speed one.
