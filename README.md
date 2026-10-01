# ScriptB

ScriptB is a small, beginner-friendly scripting language built in Python. It is designed to feel approachable for quick automation, simple programs, and learning-language fundamentals without the complexity of larger ecosystems.

## Why ScriptB?

ScriptB focuses on simplicity:

- easy syntax
- readable commands
- fast experimentation
- quick automation workflows
- built for learning and scripting

It is not trying to replace Python or Bash for every use case. Instead, it aims to be a friendly scripting language for small tasks and simple programs.

## Example

```text
print hello bscript
wait 3
repeat 3 print hello world
```

## Features

- simple print and output statements
- variable storage and retrieval
- loops with repeat
- wait and sleep commands
- if / while / for style flow control
- package import support
- script execution from files
- REPL support for quick experimentation

## Run the language

From the repository root:

```bat
run main.bat
```

Run the REPL:

```bat
scriptb.exe
```

Run a ScriptB file:

```bat
scriptb.exe example.bscript
```

Or pass a file directly from a terminal:

```bat
scriptb.exe path/to/file.bscript
```

## Example script file

```text
print This is an Example
```

Save it as `example.bscript` and run:

```bat
scriptb.exe example.bscript
```

## Repository layout

- `scriptb.exe` — compiled interpreter binary
- `bscript.exe` — bundled binary build
- `main.bat` — helper to run the default script
- `example.bscript` — basic example script
- `test.bscript` — command coverage / feature checks
- `README.md` — project overview and usage

## Learn more

- Website: https://brndn-2026.github.io/scriptb-website/
- IoT demo: https://scriptb-iot.onrender.com/

## Notes

ScriptB is still a small project and is evolving. The primary goal is to make scripting approachable, readable, and fun for beginners while still being practical for small tasks.

If you want to improve the language, contribute examples, improve the docs, or help build the ecosystem, this repo is a good place to start.
