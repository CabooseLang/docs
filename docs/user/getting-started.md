# Getting Started with Caboose

## Installing

Head on over to [our releases](https://github.com/CabooseLang/Caboose/releases) and grab the latest binary for your OS, then come on back!

## Running the REPL

Once you have a binary and have installed it run the REPL by doing:

```bash
cb
```

## Running a file

Go ahead and paste this text into your editor and save it as a Caboose file (`*.cb`)
```cb
fun hello(name) {
    print("Hello, " + name);
}

hello("world");
```

Then run it by doing:

```bash
cb path/to/your/file.cb
```

It should print `Hello, world`.
