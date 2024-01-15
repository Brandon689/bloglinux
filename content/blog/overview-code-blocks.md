+++
title = "Mud Blazor .NET 8.0 Templates has been released"
description = "Sample article showcasing syntax highlighting and formatting for Code Blocks with a custom theme."
date = 2024-01-15
draft = false

[taxonomies]
tags = ["Features","Markdown"]
[extra]
keywords = "Code, Code Blocks, Syntax, Syntax Highlighting, Theme"
toc = false
series = "Features"
+++

MudBlazor is the premier Blazor component library, with the alternative being Ant Design Blazor. Today .NET 8.0 support was merged and you can update your Visual Studio template.

```bash
dotnet new install MudBlazor.Templates
```

Interactive per Page
```bash
dotnet new mudblazor --interactivity (Auto|Server|WebAssembly)
```

Interactive Global
```bash
dotnet new mudblazor --interactivity (Auto|Server|WebAssembly) --all-interactive
```

Adding Authentication
```bash
dotnet new mudblazor --interactivity Auto --auth Individual
dotnet new mudblazor --interactivity Auto --auth Individual --all-interactive
```
