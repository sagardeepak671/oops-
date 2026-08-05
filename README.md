# OOP Interview Mastery

A reference collection for **object-oriented programming interview preparation** — a single
comprehensive PDF covering the topics that come up in technical interviews, from the four pillars
through to design patterns and SOLID principles.

---

## Contents

```
.
└── OOP Interview Mastery - Complete Edition (All 15 Parts).pdf   (~1.7 MB)
```

A consolidated 15-part guide. Typical coverage for a document of this kind:

- **The four pillars** — encapsulation, abstraction, inheritance, polymorphism
- **Classes and objects** — constructors, destructors, static members, `this`
- **Inheritance** — single, multiple, multilevel; the diamond problem and virtual inheritance
- **Polymorphism** — compile-time (overloading) vs. runtime (overriding, vtables)
- **Abstraction** — abstract classes vs. interfaces, and when each fits
- **SOLID principles** — with examples of each violation and its fix
- **Design patterns** — creational, structural, behavioural
- **Composition vs. inheritance** — the most common design question in interviews
- **Memory model** — stack vs. heap, object lifetime, RAII, garbage collection

Open the PDF for the actual contents.

---

## Reading It

```bash
git clone https://github.com/<your-username>/oops-.git
cd oops-
open "OOP Interview Mastery - Complete Edition (All 15 Parts).pdf"     # macOS
# xdg-open "OOP Interview Mastery - Complete Edition (All 15 Parts).pdf"   # Linux
# start "OOP Interview Mastery - Complete Edition (All 15 Parts).pdf"      # Windows
```

Any PDF reader works — Preview, Adobe Reader, Evince, or your browser.

---

## How to Use It

Reading an OOP guide end to end is the least effective way to prepare. What works better:

1. **Read a section, then write the code.** Implement each concept in a language you will actually
   be interviewed in. Understanding inheritance and explaining it under pressure are different
   skills.
2. **Focus on the "why" questions.** Interviewers rarely ask *what* polymorphism is; they ask *why*
   you would prefer composition over inheritance, or when an interface beats an abstract class.
3. **Prepare one worked example per pattern.** A concrete case you have actually built beats a
   textbook definition every time.
4. **Know the trade-offs.** Every OOP principle has a cost — inheritance couples, interfaces
   proliferate, patterns add indirection. Being able to name the cost is what distinguishes a strong
   answer.

---

## Related Repositories

| Repository | Contents |
|---|---|
| [`My_Leetcodes`](../My_Leetcodes) | Hard LeetCode solutions in C++ |
| [`MY_DS`](../MY_DS) | Data structures implemented from scratch |
| [`COL106_Projects`](../COL106_Projects) | Data structures and algorithms coursework |

---

## Note on Licensing

This repository stores a reference document for personal study. If the PDF was authored by a third
party, its original licence applies — please do not redistribute it commercially. Add attribution
here if you know the source.
