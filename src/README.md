# Introduction

Cottonmouth (commonly numeronymised as **c9h**) is a configuration library for
Node.js, written entirely in TypeScript.

Although "marketed" as a zero-config config, Cottonmouth has since grown to be
an extremely comprehensive and extensible library. However, at its core, it
still remains fully operational out-of-the-box!

## Configuration sources

Cottonmouth offers native support for parsing configuration values from:

* 📁 **Local filesystems** (JSON, JSON5, YAML, TOML, and INI)
* 🌐 **HTTP responses** (with full support for custom request headers, body,
etc.)
* 💻 **Environment variables** (including transforming delimited variables into
nested configuration values)
* 📋 **CLI arguments** (parsing Node.js' `process.argv` property by default)
* 📝 **Hardcoded defaults**

> This list is non-exhaustive; please see the section on **Taps** for a
> comprehensive guide on what sources Cottonmouth can parse.
>
> You'll also find guidance on creating your own taps for when you need to
> parse data from an unsupported source!
