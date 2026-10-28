<p align="center">
  <a href="https://amx.icegame.ro">
    <img src="https://amx.icegame.ro/images/logo-2.png" alt="AMX Mod X Online Compiler">
  </a>
</p>

# AMX Mod X Online Compiler

[![Website](https://img.shields.io/badge/Website-amx.icegame.ro-blue)](https://amx.icegame.ro)
[![AMXX](https://img.shields.io/badge/AMX%20Mod%20X-1.7.6%20to%201.10.0-orange)](https://amx.icegame.ro)
[![Languages](https://img.shields.io/badge/Interface-16%20languages-green)](https://amx.icegame.ro)

#### 👉 **[amx.icegame.ro](https://amx.icegame.ro)** **is a free online compiler for [AMX Mod X](https://www.amxmodx.org/) plugins (CS 1.6, HL, CZ, DoD, TFC and other GoldSrc mods).**
#### **Upload your `.sma` file or paste the source code, pick the AMX Mod X version, and download the compiled `.amxx` plugin. No local compiler setup required.**

## Why this exists

Compiling an AMX Mod X plugin normally means downloading the right AMX Mod X package, matching the compiler to your server version, and collecting every include file by hand. This compiler does it all in the browser: you pick the version, send the source, and get the `.amxx` back.

## Features

**Simple workflow**
- Upload a `.sma` file or paste the source code directly into the page
- Compiled `.amxx` plugin is available to download as soon as the build succeeds
- Compiler output can be shown on every compilation, so you can see warnings and errors line by line
- Option to automatically import the source code, so you can keep working on it

**AMX Mod X versions**
- Build against **1.7.6, 1.8.0, 1.8.1, 1.8.2, 1.8.3, 1.9.0 or 1.10.0**
- Pick the version that matches your server, so the plugin is compiled with the same includes you run in production

**Custom includes**
- If your plugin depends on an external `.inc` file that the compiler does not provide, you can upload your own include files

**Sandboxed compilation**
- Compilation runs in a sandbox, separated from the website
- Live status indicators for the database, server load and sandbox directly in the header

**Interface**
- 16 languages: English, Romanian, Italian, Hungarian, Serbian, Bulgarian, German, French, Russian, Turkish, Portuguese, Hindi, Spanish, Arabic, Japanese, Chinese
- Compilation statistics by AMX Mod X version (successful and failed builds)
- Navbar button to switch between the AMX Mod X, CounterStrikeSharp and SourceMod compilers

## How to use it

1. Go to **[amx.icegame.ro](https://amx.icegame.ro)** and pick your interface language.
2. Select the **AMX Mod X version**. Not sure which one? Use the version your server runs (type `amxx version` in the server console).
3. Select your **`.sma`** file, or paste the source code into the box.
4. If the plugin needs extra includes, press **Upload .inc** and add them first.
5. Press **Compile Now**.
6. If the build succeeds, download the compiled **`.amxx`** and upload it to `addons/amxmodx/plugins/` on your server.

## Screenshots

<details>
<summary>📸 Main page (click to expand)</summary>

<br>

[![Main page](https://github.com/barlap/amxmodx-web-compiler/blob/main/amx_main_page.PNG?raw=true)](https://github.com/barlap/amxmodx-web-compiler/blob/main/amx_main_page.PNG)

</details>

<details>
<summary>📸 Compilation result (click to expand)</summary>

<br>

[![Compilation result](https://github.com/barlap/amxmodx-web-compiler/blob/main/amx_compilation_result.PNG?raw=true)](https://github.com/barlap/amxmodx-web-compiler/blob/main/amx_compilation_result.PNG)

</details>

## Good to know

- The compiler takes a single `.sma` file. If your plugin includes custom `.inc` files, upload them with the **Upload .inc** button before compiling.
- Always compile with the AMX Mod X version that matches your server, to avoid errors caused by missing or different natives.

## Links

- Compiler: https://amx.icegame.ro
- IceGame Romania: https://icegame.ro

## Feedback

Found a bug or have a suggestion? Open an [issue](https://github.com/barlap/amxmodx-web-compiler/issues). Feedback is welcome.
