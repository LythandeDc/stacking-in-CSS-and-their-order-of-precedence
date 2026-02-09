# Stacking in CSS and their order of precedence
### Author: https://itamde.com

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

## About The Project

This code is used to help our students and those who want to progress in their learning.
Shared code for our school's students (https://itamde.com). Usable for practicing.
All rights reserved. If you want to use it for commercial purposes, it is forbidden to do so.

## Topics Covered

| # | Topic | What it demonstrates |
|---|-------|----------------------|
| 1 | **DOM Order** | Without `z-index` or `position`, elements stack by source order |
| 2 | **z-index + position** | `z-index` only works on positioned elements (`relative`, `absolute`, `fixed`) |
| 3 | **opacity context** | `opacity < 1` creates a new stacking context, isolating children |
| 4 | **transform context** | `transform` (other than `none`) also creates a new stacking context |

## Tech Stack

- HTML5 (semantic: `<main>`, `<section>`, `aria-label`)
- CSS3 (custom properties, `clamp()`, media queries, BEM naming)

## Getting Started

Open `index.html` in any modern browser. No build tools needed.

## Result

<img src="https://itamde.com/media/2023/06/zorder1.jpg" alt="Z-order Result">

HTML:
<img src="https://itamde.com/media/2023/06/zorder3.jpg" alt="Z-order Html">

CSS:
<img src="https://itamde.com/media/2023/06/zorder2.jpg" alt="Z-order CSS">

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://itamde.com/assets/images/elements/CONTRIBUTORS.svg?style=for-the-badge
[contributors-url]: https://github.com/LythandeDc/stacking-in-CSS-and-their-order-of-precedence/graphs/contributors
[forks-shield]: https://itamde.com/assets/images/elements/forks.svg?style=for-the-badge
[forks-url]: https://github.com/LythandeDc/stacking-in-CSS-and-their-order-of-precedence/network/members
[stars-shield]: https://itamde.com/assets/images/elements/stars.svg?style=for-the-badge
[stars-url]: https://github.com/LythandeDc/stacking-in-CSS-and-their-order-of-precedence/stargazers
[issues-shield]: https://itamde.com/assets/images/elements/ISSUESOPEN.svg?style=for-the-badge
[issues-url]: https://github.com/LythandeDc/stacking-in-CSS-and-their-order-of-precedence/issues
[license-shield]: https://itamde.com/assets/images/elements/LICENSEMIT.svg?style=for-the-badge
[license-url]: https://github.com/LythandeDc/stacking-in-CSS-and-their-order-of-precedence/blob/master/LICENSE.txt
[linkedin-shield]: https://itamde.com/assets/images/elements/LINKEDIN.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/company/71767248
[product-screenshot]: https://itamde.com/wp-content/uploads/2021/05/SocialLogo-3.png
