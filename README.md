# GED Math Video Lessons

A set of silent, slide-based GED math lesson videos. Each video is a 1280x720 MP4 that builds a slide deck step by step. An animated pencil cursor writes formulas and worked solutions onto each slide.

The videos have no narration, audio track, or captions.

## Landing page

`index.html` is a landing page for students. It lists each lesson file in a dropdown, plays the chosen video, shows its topics, and reminds students to use the videos as study resources.

To open it, double-click `index.html` or open it in any web browser. Students can also link straight to a lesson with `index.html?video=GED_Math_Algebra.mp4`.

## Contents

| File | Title | Length | Slides | Topics covered |
|---|---|---|---|---|
| `GED_Math_Algebra.mp4` | Algebraic Problem Solving: Syllabus Gap Lessons | 4:01 | 20 | Multiplying binomials, rational expressions, real-world linear equations, systems and inequalities, graphing with intercepts, lines through two points, functions |
| `GED_Math_Data_Lab_Sample.mp4` | Data Lab: Sample Data Sets Beyond the Syllabus | 1:28 | 7 | Worked data sets: speed and distance, savings, a thrown-ball height model, percent difference |
| `GED_Math_Essentials.mp4` | GED Math Essentials: Expanded Details | 3:48 | 20 | Multiples, factors, LCM and GCF, exponents, percent change, using the calculator, volume of prisms and cylinders, the distributive property, slope, mean, median, mode and range, finding errors, exam strategy |
| `GED_Math_Quantitative.mp4` | Quantitative Problem Solving: Syllabus Gap Lessons | 3:56 | 20 | Scientific notation, multistep ratios and unit conversion, weighted averages, dot plots and histograms, counting techniques, composite area and perimeter, the Pythagorean theorem |
| `GED_Mathematics_Applications.mp4` | Understanding Coordinate Planes | 4:33 | 24 | Coordinate planes, linear graphs, equations of lines, functions, quadratic equations, exponent rules, geometry basics, circles, surface area, statistics, tables and graphs, final review |
| `GED_Mathematics_Applications_25_Slides.mp4` | Welcome to GED Mathematical Applications | 5:07 | 25 | Plotting points, slope, equations of lines, systems of linear equations, factoring quadratics, exponent rules, scientific notation, geometry, circles, surface area, statistics, tables and graphs, mixed practice exam |
| `GED_Mathematics_Foundations.mp4` | Introduction to GED Mathematics | 4:47 | 25 | Place value, multiplication and division, order of operations, fractions, decimals, ratios and proportions, unit rates, discounts, introduction to algebra, simplifying expressions, multistep equations, translating word problems, review |
| `GED_Mathematics_Foundations_25_Slides_1_.mp4` | Welcome to GED Mathematics | 6:04 | 25 | Whole numbers and rounding, place value, order of operations, adding, subtracting, multiplying and dividing fractions, decimals, ratios and proportions, percentages, discounts and sales tax, introduction to algebra, one-step equations, assessment |

## Repository layout

```
ged-math-videos/
├── index.html
├── README.md
├── .gitignore
└── videos/
    └── *.mp4
```

`index.html` loads the files in `videos/` using relative paths, so keep the folder structure as it is.

## Notes

- Some videos cover overlapping material. `GED_Mathematics_Foundations` and `GED_Mathematics_Foundations_25_Slides_1_` both cover arithmetic fundamentals and early algebra. `GED_Mathematics_Applications` and `GED_Mathematics_Applications_25_Slides` overlap in the same way.
- Adding a transcript or caption file for each video would make the lessons easier to use with screen readers and would help learners who study without sound.

## Getting started

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/ged-math-videos.git
cd ged-math-videos
```

Then open `index.html` in a web browser.

## Sharing the landing page with students

GitHub Pages can host the landing page so students only need a link:

1. On GitHub, open the repository and go to **Settings**, then **Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and the `/ (root)` folder, then save.

After a minute or two, the page will be available at `https://YOUR-USERNAME.github.io/ged-math-videos/`.
