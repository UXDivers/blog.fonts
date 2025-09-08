# Deep Dive: How to Integrate Google Fonts in .NET MAUI

A small .NET MAUI sample that accompanies the Grial blog post "Deep Dive: How to Integrate Google Fonts in .NET MAUI". The project demonstrates how to include and register custom fonts in a MAUI app and contains example font files under `Resources/Fonts`.

## Quick overview
This repository shows a minimal workflow for adding and using custom fonts with .NET MAUI:
- Add font files to `Resources/Fonts/`.
- Register fonts in the project (either in the csproj as `<MauiFont>` entries, or via the shared `Fonts.xaml`/styles).
- Use the registered font aliases in XAML or C# styles.

## Prerequisites
- .NET SDK (matching the project target; repository contains net9.0 build artifacts).
- MAUI workloads installed (via Visual Studio or the `dotnet` CLI).
- Visual Studio 2022/2023 (Windows) or Visual Studio for Mac / Visual Studio (Mac) for simulator/device runs, or use the `dotnet` CLI to build.

## Files of interest
- `Resources/Fonts/` — bundled font files.
- `Resources/Styles/Fonts.xaml` — where shared font styles may live.

## License
This repository includes a top-level `LICENSE` file. Check it for terms governing use and redistribution.

This project uses the following fonts:

- [Montserrat](https://fonts.google.com/specimen/Montserrat)  
- [Poppins](https://fonts.google.com/specimen/Poppins)

Both fonts are provided by [Google Fonts](https://fonts.google.com/) and are distributed under the **SIL Open Font License, Version 1.1**.

Copies of the licenses are included in the [`source/blog.fonts/Resources/Fonts/Licenses/`](./source/blog.fonts/Resources/Fonts/Licenses) directory.

