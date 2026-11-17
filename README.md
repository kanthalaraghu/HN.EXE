# HN.EXE

A simple Hacker News desktop client for Windows built with WinUI 3.

I spend a lot of time browsing Hacker News and wanted something that felt lighter than opening a browser tab every time. Most existing clients either looked outdated or tried to do too much.

HN.EXE is an attempt to make Hacker News feel like a native desktop application while keeping the interface focused and distraction-free.

The design takes inspiration from terminal applications, IRC clients, developer tools, and modern chat applications.

---

## Features

- Browse Top Stories
- Browse New Stories
- Browse Best Stories
- Ask HN
- Show HN
- Jobs
- Threaded comments
- Fast keyboard navigation
- Built-in article viewer
- Bookmark stories
- Refresh without restarting
- Dark developer-friendly interface

---

## Screenshots

Coming soon.

---

## Why I Built This

Most of my daily reading happens on Hacker News.

I wanted:

- a cleaner reading experience
- keyboard-first navigation
- a desktop app that feels native on Windows
- something visually inspired by terminal software rather than traditional news readers

This project started as a weekend experiment and gradually became a proper application.

---

## Technology

- .NET 8
- WinUI 3
- Windows App SDK
- Hacker News Firebase API
- MVVM Toolkit

---

## Project Structure

```
HN.EXE
│
├── Models
├── Services
├── ViewModels
├── Views
├── Controls
├── Assets
└── Helpers
```

---

## Keyboard Shortcuts

| Shortcut | Action |
|-----------|---------|
| J | Next story |
| K | Previous story |
| O | Open article |
| C | Focus comments |
| R | Refresh |
| Ctrl + P | Command palette |

---

## Planned Features

- Article reading mode
- Offline cache
- Multiple themes
- Search
- Better comment rendering
- User profiles
- Story filtering

---

## Building

Requirements:

- Visual Studio 2022
- Windows App SDK
- .NET 8 SDK

Clone the repository:

```bash
git clone https://github.com/kanthalaraghu/HN.EXE.git
```

Open the solution:

```bash
HN.EXE.sln
```

Build and run.

---

## Contributing

Bug reports, suggestions, and pull requests are welcome.

If you find something that can be improved, feel free to open an issue.

---

## Acknowledgements

Hacker News is operated by Y Combinator.

Data is provided through the official Hacker News Firebase API.

---

## Author

Kanthala Raghu

GitHub:
https://github.com/kanthalaraghu

---

## License

MIT
