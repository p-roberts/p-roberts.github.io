---
layout: essay
type: essay
title: "Are “coding standards” significant if functionality of code works?"
# All dates must be YYYY-MM-DD format!
date: 2025-06-27
published: true
labels:
  - Coding Standards
  - ESLint
  - pyLint
  - cppcheck
  - Prettier
  - clang-format
---


<img width="523" alt="Img source  (hongkiat com) 2" src="https://github.com/user-attachments/assets/92dd4009-e185-48bd-a0c3-3f7eb5c29220" />
*Img source  (hongkiat.com)*


*ARE “CODING STANDARDS” SIGNIFICANT IF FUNCTIONALITY OF CODE WORKS?*

Coding standards can vary between programming languages, like JavaScript, Python, and C++. For instance, coding standards of syntax and structure can be defined by curly braces in JavaScript, but by indentation in Python, or naming conventions of camelCase or snake_case. Although, these standards would affect the execution of a code, some standards are more trivial than others. One example is spacing. To review spacing coding standards, I provided some common JavaScript spacing rules provided by WordPress Developer Resources: 
<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px;">
These rules encourage liberal spacing for improved developer readability. The minification process creates a file that is optimized for browsers to read and process.
  <br>
  <br>
•	Indentation with tabs.
  <br>
•	No whitespace at the end of line or on blank lines.
  <br>
•	Lines should usually be no longer than 80 characters, and should not exceed 100 (counting tabs as 4 spaces). This is a “soft” rule, but long lines generally indicate unreadable or disorganized code.
  <br>
•	if/else/for/while/try blocks should always use braces, and always go on multiple lines.
  <br>
•	Unary special-character operators (e.g., ++, --) must not have space next to their operand.
  <br>
•	Any , and ; must not have preceding space.
  <br>
•	Any ; used as a statement terminator must be at the end of the line.
  <br>
•	Any : after a property name in an object definition must not have preceding space.
  <br>
•	The ? and : in a ternary conditional must have space on both sides.
  <br>
•	No filler spaces in empty constructs (e.g., {}, [], fn()).
  <br>
•	There should be a new line at the end of each file.
  <br>
•	Any ! negation operator should have a following space.*
  <br>
•	All function bodies are indented by one tab, even if the entire file is wrapped in a closure.*
  <br>
•	Spaces may align code within documentation blocks or within a line, but only tabs should be used at the start of a line.* </div>
( *JavaScript Coding Standards – Coding Standards Handbook | Developer.WordPress.org, 2019* )

## IF IT AIN’T BROKE, DON’T FIX IT, RIGHT?

How pertinent are these coding standards, or is it insignificant if your code source runs precisely as expected? When we include the collaborative projects, we must understand the importance of readability amongst your team. Or how about industry standards? Upholding an industry standard increases consistency and ease in using, sharing, or editing your source code. 
Many programming languages’ similarities in coding standards, incorporate the tools to help enforce their coding standards. Linting tools like JavaScript’s ESLint, or pylint (Python), and cppcheck (C++) to analyze and detect source code errors, inconsistencies, or discrepancies in coding standards. Formatters like Python’s Black, Prettier for JavaScript, or clang-format for C++, that will format code to the stylistic format of a specified code standard. There are Integrated Development Environments (IDE) that support these tools with installed extensions and plugins. VS Code offers several options of readily available extensions.

## COMPARE AND CONTRAST

Following my experimentation with ESLint and Prettier with Visual Studio Code (VS Code), has cutdown the time to write code greatly with the ease and speed. It’s like typing an essay with preformatted templates and autocorrect guiding my grammar and punctuation mistakes. Just as a well- formatted essay in a language I understand, e.g., American English, it becomes easier for me to read (along with my Professors, of course). Therefore, I would say that coding standards are as significant, especially when considering collaborative projects, industry standards, and program maintenance. In concluding this essay, I leave the four key benefits of using coding standards by Perforce Software:
<br>
<div style="border: 1px solid #ccc; padding: 10px; margin: 10px;">
There are four key benefits of using coding standards:
  <br>
1. Compliance with industry standards (e.g., ISO).
  <br>
2. Consistent code quality — no matter who writes the code.
  <br>
3. Software security from the start.
  <br>
4. Reduced development costs and accelerated time to market. </div>  
( *Intro to Coding Standards — Coding Rules and Guidelines | Perforce Software, n.d.* )


