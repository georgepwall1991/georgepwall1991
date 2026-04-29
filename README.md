# George Wall

I build production-safety tooling for .NET teams: analyzers, developer workflows, and small sharp utilities that catch expensive mistakes before they ship.

Most of my open-source work sits around Roslyn analyzers, configuration safety, dependency injection correctness, EF Core performance, and runtime behavior that should be visible before production.

[![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![Roslyn](https://img.shields.io/badge/Roslyn-5C2D91?style=flat-square&logo=visualstudio&logoColor=white)](https://github.com/dotnet/roslyn)
[![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)](https://learn.microsoft.com/dotnet/csharp/)
[![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)](https://www.swift.org/)
[![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)](https://www.rust-lang.org/)

## Featured Work

| Project | What it catches |
| --- | --- |
| [ConfigContraband](https://github.com/georgepwall1991/ConfigContraband) | Configuration binding bugs, missing sections, duplicate JSON members, and option-shape drift. |
| [LinqContraband](https://github.com/georgepwall1991/LinqContraband) | EF Core and LINQ query traps like N+1s, client-side evaluation, and costly query shapes. |
| [DependencyInjection.Lifetime.Analyzers](https://github.com/georgepwall1991/DependencyInjection.Lifetime.Analyzers) | Captive dependencies, lifetime mismatches, and DI registrations that look fine until runtime. |
| [automapper-analyser](https://github.com/georgepwall1991/automapper-analyser) | AutoMapper configuration mistakes that otherwise wait until runtime to fail. |

## Current Focus

- Turning repeat production review feedback into compile-time diagnostics.
- Keeping analyzer rules precise enough that developers trust the warning.
- Building tools that explain the fix, not just the failure.
- Shipping small, useful packages with tests, docs, and release automation.

## Stack

`.NET` / `C#` / `Roslyn` / `ASP.NET Core` / `EF Core` / `TypeScript` / `React` / `SwiftUI` / `Rust`

## Working Style

I like boring reliability, fast feedback, clean diagnostics, and tools that pay for themselves the first time they stop a bad deploy.
