# Malmö Programming in C# II — Assignment Solutions

Complete solutions to the six assignments of the course **Programming in C#, II** (Malmö University course material, C# II VT19/VT20), written by **Abel Haile Magicho** following each assignment's instructions exactly, including the VG (higher-grade) extra tasks where the assignment offers them.

## Contents

For every assignment N from 1 to 6 this repository holds two files:

| File | What it is |
|---|---|
| `malmo-assignment-N-solution.zip` | The complete Visual Studio solution source for Assignment N — projects, source files, and the real program output saved as output.txt inside. Download and unzip, then open the project in Visual Studio or build with the .NET SDK. |
| `malmo-csharp-assignment-N-explainer.pdf` | The explainer for Assignment N: what the assignment asks, how the code answers it step by step, the full code, the real run output, and a glossary. |

## The assignments

1. **Apu's Animal Motel, Version 1** — classes, encapsulation, inheritance and dynamic binding: Animal, Mammal and Bird categories, Dog, Cat, Dove and Eagle species, and the AnimalManager.
2. **Animal Motel, Version 2** — interfaces and abstract classes: IAnimal, abstract species with eater types and food schedules, the FoodSchedule class, and two sorting routes.
3. **Animal Motel, Version 3** — generics: IListManager\<T\> and ListManager\<T\> under the whole program, recipes, staff, and a food-schedule dictionary.
4. **Animal Motel, Version 4** — files, serialization and exceptions: binary, XML and text save and load, an AnimalFactory, and a custom AnimalMotelException.
5. **The Control Tower** — delegates and events in WPF: the Airplane as publisher, the control tower and a flight logger as subscribers.
6. **Invoice Maker** — WPF and text files: reads the course demo file InvoiceDemo1.txt and produces the invoice with line totals, tax, totals and discount.

## Verification

Every project was compiled with the .NET 8 SDK — **build succeeded, 0 errors** for all six. The Windows Forms and WPF interfaces run on Windows; on the Linux machine where these solutions were built, the interfaces compile but cannot display, so every part of the behaviour that can execute without a screen was run for real through console harnesses that link the actual solution source files. That real output is saved as output.txt inside each solution ZIP and printed verbatim in each explainer PDF. Highlights: the Assignment 6 invoice totals come out at **3145.95 with 541.40 tax included**, exactly as the demo data requires.

## Author

Abel Haile Magicho — [github.com/kembAB](https://github.com/kembAB)
