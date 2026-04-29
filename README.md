<p align="center">
  <img src="assets/profile-hero.svg" alt="George Wall - production-safety tooling for .NET teams" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/georgepwall1991/ConfigContraband"><img alt="ConfigContraband" src="https://img.shields.io/badge/ConfigContraband-configuration%20safety-22c55e?style=for-the-badge"></a>
  <a href="https://github.com/georgepwall1991/LinqContraband"><img alt="LinqContraband" src="https://img.shields.io/badge/LinqContraband-query%20safety-38bdf8?style=for-the-badge"></a>
  <a href="https://github.com/georgepwall1991/DependencyInjection.Lifetime.Analyzers"><img alt="DI analyzers" src="https://img.shields.io/badge/DI%20Analyzers-lifetime%20safety-f59e0b?style=for-the-badge"></a>
</p>

## Signal

I build production-safety tooling for .NET teams: Roslyn analyzers, developer workflows, and focused utilities that catch expensive mistakes before they ship.

The thread running through my work is simple: make the failure visible while the developer is still in the editor, keep the diagnostic precise enough to trust, and ship the fix with tests, docs, and release automation.

## Featured Systems

| Project | Focus | Why it matters |
| --- | --- | --- |
| [ConfigContraband](https://github.com/georgepwall1991/ConfigContraband) | Configuration correctness | Catches broken `appsettings`, missing sections, duplicate JSON members, and option-shape drift before runtime. |
| [LinqContraband](https://github.com/georgepwall1991/LinqContraband) | EF Core and LINQ safety | Flags query shapes that cause client-side evaluation, N+1s, cartesian explosions, and costly production behavior. |
| [DependencyInjection.Lifetime.Analyzers](https://github.com/georgepwall1991/DependencyInjection.Lifetime.Analyzers) | Dependency injection lifetimes | Detects captive dependencies, unsafe scopes, and lifetime mismatches that usually fail late. |
| [CancelCop.Analyzer](https://github.com/georgepwall1991/CancelCop.Analyzer) | CancellationToken discipline | Keeps cancellation flowing through public APIs, handlers, EF Core, HTTP calls, and Minimal APIs. |
| [automapper-analyser](https://github.com/georgepwall1991/automapper-analyser) | Mapping safety | Moves AutoMapper configuration failures from runtime surprises into compile-time feedback. |
| [CPMigrate](https://github.com/georgepwall1991/CPMigrate) | Package management | Helps .NET solutions move to Central Package Management with dependency health checks and rollback. |

## Toolbox

<p>
  <img alt=".NET" src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white">
  <img alt="C Sharp" src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white">
  <img alt="Roslyn" src="https://img.shields.io/badge/Roslyn-5C2D91?style=flat-square&logo=visualstudio&logoColor=white">
  <img alt="ASP.NET Core" src="https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white">
  <img alt="EF Core" src="https://img.shields.io/badge/EF%20Core-0f766e?style=flat-square&logo=dotnet&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-087EA4?style=flat-square&logo=react&logoColor=white">
  <img alt="Swift" src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
</p>

## Current Bias

- High-signal analyzers over noisy rule volume.
- Runtime failures converted into compile-time feedback.
- Developer-facing diagnostics that explain the fix, not just the failure.
- Small packages that are documented, tested, versioned, and releasable.

## Working Style

I like boring reliability, fast feedback, clean diagnostics, and tools that pay for themselves the first time they stop a bad deploy.
