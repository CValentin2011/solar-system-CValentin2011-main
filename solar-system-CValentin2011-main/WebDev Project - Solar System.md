#project/outline #programming #webdev #htmlcss
# **CSS Snowman**

## Summary

In this project, we'll use the **animation** property along with **keyframes** to create a proportional solar system, where the planets orbit the Sun at the same rate they would if we made the Earth orbit 365 days. You'll also be tasked with creating two **embellishments** to your project, details you define and make from scratch like shooting stars, aliens, or anything else you can think of. 

---
## **Part I: The Solar System**

*Using the template provided, create an animated solar system.*

- [ ] **8-9 Planets:** There are at least 8 planets defined in the HTML and styled in the CSS.
- [ ] **Circular Motion:** All planets move in a circular orbit around the Sun using `rotate()` and `translateX()` keyframes.
- [ ] **Shooting Star:** At least one shooting star is animated to "fly" across the screen.
- [ ] **Background:** The `body` has a space-themed background image that covers the entire viewport.
- [ ] **Basic Documentation:** The CSS and HTML include initial comments explaining what the code is doing.

## **Part II: Proportions

*For this part, you must modify the orbits to be proportional to their relative *

- [ ] **Proportional Orbits:** Planet `animation-duration` values are mathematically calculated based on Earth’s 365.25-day orbit.

> [!Note]
> 
> ### The Proportional Formula
> 
> Your orbits must be mathematically accurate. Use this formula to calculate the `animation-duration` for each planet:
> 
> Target Planetary Orbit = (Target Orbit in Earth Days) / (365.25 Actual Planet Days) × (Earth Speed (s))
> 
> **Example:** If you want your **Earth** to orbit in **10 seconds**, and you are calculating for **Mars** (687 days):
> 
> 1. 687/365.25 = 1.88
> 2. 1.88×10 = 18.8
> 3. **Mars duration:** `18.8s`

- [ ] **Shooting Star Timing:** Shooting stars use `animation-delay` and `infinite` repeats so they occur at different times rather than just once.
- [ ] **Grouped Styling:** CSS is organized with generalized styles (like `body` or `.planets`) grouped together in the same area.
 - [ ] **Planet Spin:** The planets themselves rotate on their own axis (spin) while they move around the Sun.
## **Part III: Styling & Advanced Techniques**

- [ ] **Two Embellishments:** At least two extra items are included (e.g., a UFO on a Bezier curve, a comet, or the ISS).
- [ ] **Top-Down Organization:** Try to take a “largest to smallest” approach, where the more generalized stylings (body, \*, etc.) are higher up in the styling order.
---

## **Grading Schema**

Each grading specification follows the list below. Each specification is as follows:

- [ ] The Solar System
- [ ] Proportions
- [ ] Embellishment I
- [ ] Embellishment II
### Point Allocation Table - Summative Assignment Features (General)

| Score | Problem Solving                                                                                                                                  |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| 5     | Response gives evidence of a complete understanding of the problem; is fully developed; is clearly communicated.                                 |
| 4     | Response gives the evidence of a clear understanding of the problem but contains minor errors or is not fully communicated.                      |
| 3     | Response gives evidence of a reasonable approach but indicates gaps in conceptual understanding. Explanations are incomplete, vague, or muddled. |
| 2     | Response gives some evidence of problem understanding but contains major programming or reasoning errors.                                        |
| 1     | No response or response is completely incorrect or irrelevant.                                                                                   |

