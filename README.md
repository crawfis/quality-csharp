# AI Bootcamp - Quality Project (C#)

This is your template for building projects with professional AI-assisted workflows. The AI will guide you through the Engineering Design Process — Ask, Imagine, Plan, Create, Improve — and produce clean, well-structured code. You'll learn professional practices by example.

## Setup

1. Install the .NET SDK: https://dotnet.microsoft.com/download
   - Download the latest .NET 8 LTS version for your operating system.

2. Install Visual Studio (recommended): https://visualstudio.microsoft.com/
   - Select the ".NET desktop development" workload during installation.
   - Alternatively, use VS Code with the C# Dev Kit extension.

3. Verify .NET works:
   ```
   dotnet --version
   ```

4. Run the hello world to test:
   ```
   cd src/QualityProject
   dotnet run
   ```

## Using AI Tools

### Claude Code (recommended)
1. Install Claude Code: https://docs.anthropic.com/en/docs/claude-code
2. Open a terminal in this folder
3. Run `claude` and start describing what you want to build
4. Claude will guide you through the Engineering Design Process

### Cursor
1. Install Cursor: https://cursor.com
2. Open this folder in Cursor
3. Use the AI chat to start building

### GitHub Copilot
1. Install the Copilot extension in Visual Studio or VS Code
2. Open the solution (QualityProject.sln) in Visual Studio
3. Use Copilot Chat to start building

## Running Code

```
cd src/QualityProject
dotnet run
```

## Installing Packages

```
cd src/QualityProject
dotnet add package PackageName
```

## Running Tests

```
dotnet test
```

## What To Expect

The AI will guide you through 5 phases:

1. **Ask** — discuss what you want to build
2. **Imagine** — explore ideas and approaches
3. **Plan** — break the project into steps before writing code
4. **Create** — write tests first, then implement
5. **Improve** — review, debug, and refine the code

Don't worry if this seems like a lot — the AI handles the process. You just describe what you want to build and learn from the results.

## Suggested Libraries

| Library | What It Does |
|---------|-------------|
| **WinForms** | Create desktop apps with buttons, windows, menus (Windows) |
| **Blazor** | Build web apps with C# instead of JavaScript |
| **Spectre.Console** | Make beautiful terminal output with colors and tables |
| **xUnit** | Write and run tests for your code |

## Starting a New Project

Clone a fresh copy of this template for each new project:
```
git clone <repo-url> my-new-project
```

## Start Building!

Tell the AI what you want to build! Examples:
- "Build me a desktop calculator with WinForms"
- "Create a command-line task manager with Spectre.Console"
- "Make a personal diary app"
