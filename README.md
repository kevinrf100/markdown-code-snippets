# Markdown Code Snippets

A comprehensive VS Code extension that provides code block snippets for Markdown files, supporting popular programming languages and formats.

## Features

- 🚀 **Multiple Languages** - Snippets for the most commonly used programming languages
- 📦 **Well Organized** - Snippets grouped by category (Languages, Data Formats, Config, Database)
- ⚡ **Fast & Simple** - Just type the language name and press Tab
- 🎯 **Cursor Positioning** - Automatically places your cursor inside the code block

## Installation

1. Open VS Code
2. Press `Cmd+Shift+X` (macOS) or `Ctrl+Shift+X` (Windows/Linux) to open Extensions
3. Search for "Markdown Code Snippets"
4. Click Install

Or install from the command line:

```bash
code --install-extension markdown-code-snippets
```

## Extension quickstart

[Vscode extension quick start](vsc-extension-quickstart.md)

## Usage

When editing a Markdown file, simply type the language name and press `Tab` to insert a code block.

### Quick Examples

**Python:**
Type `python` + Tab

```python
def hello():
    print("Hello, World!")
```

**JavaScript:**
Type `javascript` or `js` + Tab

```javascript
function hello() {
  console.log("Hello, World!");
}
```

**Bash:**
Type `bash` + Tab

```bash
#!/bin/bash
echo "Hello, World!"
```

**SQL:**
Type `sql` + Tab

```sql
SELECT * FROM users WHERE active = true;
```

### Common Languages

| Prefix | Language |
|--------|----------|
| `python` | Python |
| `javascript` or `js` | JavaScript |
| `typescript` or `ts` | TypeScript |
| `java` | Java |
| `cpp` | C++ |
| `csharp` | C# |
| `go` | Go |
| `rust` | Rust |
| `php` | PHP |
| `ruby` | Ruby |

### Web Development

| Prefix | Language |
|--------|----------|
| `html` | HTML |
| `css` | CSS |
| `scss` | SCSS |
| `sass` | Sass |
| `less` | Less |
| `vue` | Vue |
| `svelte` | Svelte |

### Shell & Scripts

| Prefix | Language |
|--------|----------|
| `bash` | Bash |
| `sh` | Shell |
| `powershell` | PowerShell |
| `bat` | Batch |

## Supported Languages

### Languages

**Backend:** `python`, `java`, `csharp`, `c`, `cpp`, `go`, `rust`, `ruby`, `php`, `perl`, `r`, `lua`

**Frontend:** `javascript`, `js`, `typescript`, `ts`, `html`, `css`, `scss`, `sass`, `less`, `vue`, `svelte`

**Mobile:** `swift`, `kotlin`, `dart`, `objectivec` (prefix: `objc`)

**JVM:** `scala`, `groovy`

**Functional:** `haskell`, `elixir`, `erlang`, `clojure`

**Shell:** `bash`, `sh`, `powershell`, `bat`

**Other:** `graphql`, `latex`, `tex`, `markdown`, `diff`

### Data Formats

`json`, `yaml`, `yml`, `xml`, `toml`, `csv`

### Config Files

`ini`, `properties`, `dotenv`, `env`, `dockerfile`, `dockerignore`, `gitignore`, `nginx`, `apache`, `makefile`

### Database

`sql`, `mysql`, `postgresql`, `plsql`, `tsql`, `mongodb`, `redis`

### Utilities

`text`, `log`

## Tips & Tricks

1. **Quick Documentation**: Use code blocks to document API examples, configuration snippets, or command-line instructions
2. **Multi-language Projects**: Quickly switch between different language blocks in your documentation
3. **README Files**: Perfect for creating comprehensive README.md files with multiple code examples

### Example Workflow

When documenting a web project in your README:

1. Type `html` + Tab for HTML structure
2. Type `css` + Tab for styling examples
3. Type `javascript` + Tab for functionality examples
4. Type `bash` + Tab for installation commands

## 🤝 Contributing

Contributions are welcome ❤️! If you'd like to add more languages or improve existing snippets:

1. Fork the repository
2. Make your changes
3. Submit a pull request

## License

MIT

## Release Notes

### 0.0.1

Initial release with support for popular programming languages, data formats, config files, and databases

---

**Enjoy!** 🎉
