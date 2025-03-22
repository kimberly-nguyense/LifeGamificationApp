# Life Gamification App

A desktop application inspired by The Sims that helps track your energy, focus, and productivity with status bars. I built this to help manage my ADHD symptoms and make daily tasks more engaging through gamification.

## What It Does

- Shows a small overlay on your desktop with status bars (like in The Sims)
- Tracks things like energy, focus, and mood
- Gives you points and achievements for completing tasks
- Helps visualize when you need to take breaks or refocus
- Stores your data locally so you can see trends over time

## Tech Stack

- C# and WPF for the UI
- .NET 8.0
- Entity Framework for database operations
- Followed MVVM pattern (Model-View-ViewModel)

## Setup Instructions

### Requirements
- Visual Studio 2022
- .NET 8.0
- Windows 10 or 11

### How to Run
1. Clone this repo
2. Open the solution file in Visual Studio
3. Hit F5 to build and run

## Project Status

This is my first major project after graduating! I'm building this as a portfolio piece to show what I've learned and to practice C# development. Currently working on:

- [x] Setting up project structure with Clean Architecture
- [ ] Setting up the basic window overlay
- [ ] Creating the status bar UI
- [ ] Adding database storage
- [ ] Implementing point system
- [ ] Building achievement system

More features planned based on time and feedback!

## Project Structure

Following clean architecture principles:
```
LifeGamificationApp/
├── LifeGamificationApp.Core/            # Domain models, interfaces, business logic
├── LifeGamificationApp.Infrastructure/  # Data access, external services
└── LifeGamificationApp.UI/              # WPF application, ViewModels, Views
```

## Screenshots

Coming soon! (Once I have the UI working properly)

## Why I Built This

As someone with ADHD, I've always been more productive when things feel game-like. I wanted to create something that would help me stay focused while also serving as a good portfolio project to show potential employers.

Key things I'm learning:
- WPF development
- Working with databases in C#
- Clean Architecture principles
- Software architecture patterns
- How to plan and execute a project from scratch

## License

MIT License

---

Any feedback or suggestions are welcome! Feel free to open an issue or reach out.