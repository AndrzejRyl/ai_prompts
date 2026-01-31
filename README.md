# AI Prompts

A collection of reusable AI prompts organized by technology stack.

## Philosophy

These prompts are designed to be:

- **Short** - Minimal token usage to preserve context window for actual work
- **Focused** - Each prompt does one thing well
- **Technology-specific** - Organized by stack for maximum relevance
- **Copy-paste ready** - No setup, no dependencies, just use them

This is not a framework or skill system. It's a personal toolkit of shortcuts that make AI agents do exactly what you need, fast.

## Structure

```
ai_prompts/
├── android/      # Android/Kotlin prompts
├── ios/          # iOS/Swift prompts
├── django/       # Django/Python prompts
├── reactjs/      # React/JavaScript prompts
└── README.md
```

## Usage

1. Navigate to the relevant technology folder
2. Find the prompt that matches your task
3. Copy and paste into your AI tool
4. Optionally append project-specific context

## Adding Prompts

When adding new prompts:

- One prompt per file
- Use descriptive filenames (e.g., `fix-migration.md`, `add-viewmodel.md`)
- Include minimal context - let the AI figure out the rest from your codebase

## Why Technology-Specific?

AI agents perform better with stack-specific instructions. A prompt that works great for React components may produce subpar results for SwiftUI views. Separating by technology:

- Reduces ambiguity
- Enables framework-specific best practices
- Avoids "one size fits all" compromises

## License

MIT
