---
layout: essay
type: essay
title: "Are coding standards significant if functionality of code works?"
# All dates must be YYYY-MM-DD format!
date: 2026-06-22
published: false
labels:
  - Coding Standards
  - ESLint
  - pyLint
  - cppcheck
  - Prettier
  - clang-format
  - Error Lens
---
<img width="523" alt="Img source  (hongkiat com) 2" src="https://github.com/user-attachments/assets/92dd4009-e185-48bd-a0c3-3f7eb5c29220" />
<br>
*image source: hongkiat.com*

## ARE CODING STANDARDS SIGNIFICANT IF FUNCTIONALITY OF CODE WORKS?

Coding standards vary between programming languages, like JavaScript, Python, and C++. For instance, syntax and structure can be defined by curly braces in JavaScript, by indentation in Python, or by naming conventions like camelCase or snake_case. These standards affect how code executes, but some are more trivial than others — spacing being a good example. To illustrate, here are some common JavaScript spacing rules from WordPress Developer Resources:

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px;">
These rules encourage liberal spacing for improved developer readability. The minification process creates a file that is optimized for browsers to read and process.
  <br>
  <br>
  
  <details>
  
•	Indentation with tabs.
  
•	No whitespace at the end of line or on blank lines.

•	Lines should usually be no longer than 80 characters, and should not exceed 100 (counting tabs as 4 spaces). This is a "soft" rule, but long lines generally indicate unreadable or disorganized code.

•	if/else/for/while/try blocks should always use braces, and always go on multiple lines.

•	Unary special-character operators (e.g., ++, --) must not have space next to their operand.

•	Any , and ; must not have preceding space.

•	Any ; used as a statement terminator must be at the end of the line.

•	Any : after a property name in an object definition must not have preceding space.

•	The ? and : in a ternary conditional must have space on both sides.

•	No filler spaces in empty constructs (e.g., {}, [], fn()).

•	There should be a new line at the end of each file.

•	Any ! negation operator should have a following space.

•	All function bodies are indented by one tab, even if the entire file is wrapped in a closure.

•	Spaces may align code within documentation blocks or within a line, but only tabs should be used at the start of a line.

</details>

</div>

(*JavaScript Coding Standards – Coding Standards Handbook, Developer.WordPress.org, 2019*)

## IF IT AIN'T BROKE, DON'T FIX IT, RIGHT?

How pertinent are these coding standards — or is it insignificant if your code runs precisely as expected? When we consider collaborative projects, we have to think about readability among teammates. Or industry standards: upholding one increases consistency and makes it easier to use, share, or edit source code.

Luckily, many programming languages offer tools to help enforce their coding standards, adding ease to the writing process. Linting tools like JavaScript's ESLint, Python's pylint, and C++'s cppcheck analyze code to detect errors, inconsistencies, or deviations from a given coding standard. Formatters like Python's Black, JavaScript's Prettier, or C++'s clang-format reformat code to match a specified style. And on top of that, Integrated Development Environments (IDEs) support these tools through installed extensions and plugins — Visual Studio Code (VS Code) alone offers several readily available options.

## COMPARE AND CONTRAST

My experimentation with ESLint and Prettier in VS Code has cut down the time it takes me to write code. It's like typing an essay with preformatted templates — autocorrect catching my grammar and punctuation mistakes along the way. The time saved was most noticeable in my last couple of projects. While learning how to build a webpage, my estimated completion time was nearly cut in half thanks to ESLint and Prettier. I've also installed Error Lens by Alexander, which makes errors stand out even more during a time crunch or a quiz.

These extensions have added confidence to my coding, since it's often the smallest thing — a missing semicolon, a mismatched bracket — that triggers a syntax error. They've also saved me the frustration of getting stuck on parse-time or compile-time errors, catching the issue before it derails an entire run.

Just as a well-formatted essay in a language I understand is easier for me—and my professors—to read, code becomes easier to comb through between collaborators, whether through tools like ESLint or by manually enforcing schemes and standards. So whether you use these tools or enforce standards yourself, I'd say they are very necessary. Coding standards are significant — especially when collaboration, industry standards, and long-term maintenance are on the line. I'll leave off with the four key benefits of coding standards, as outlined by Perforce Software:





<div style="border: 1px solid #ccc; padding: 10px; margin: 10px;>
  
**4 Key Benefits of Using Coding Standards**

| # | Key Benefit |
|---|---|
| 1 | Compliance with industry standards (e.g., ISO) |
| 2 | Consistent code quality — no matter who writes the code |
| 3 | Software security from the start |
| 4 | Reduced development costs and accelerated time to market |

</div>

(*Intro to Coding Standards — Coding Rules and Guidelines, Perforce Software, n.d.*)
