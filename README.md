# PocketFlow - AI-Powered Code Generation Templates

<p align="center">
  <a href="https://github.com/MattJonesIntel/PocketFlow" target="_blank">
    <img
      src="./assets/banner.png" width="800"
    />
  </a>
</p>

A comprehensive template system for generating Python utilities with AI assistance. PocketFlow provides structured templates and workflows for creating well-organized, documented Python scripts that can be integrated into larger utility collections.

This project extends the original [Pocket Flow](https://github.com/The-Pocket/PocketFlow) framework with Intel-specific templates and workflows for Agentic Coding development.

## 🎯 Purpose

PocketFlow serves as a **template generation system** that creates standardized Python utilities, which can then be organized into repositories like [python-utilities](https://github.com/MattJonesIntel/python-utilities). It bridges the gap between AI-generated code and production-ready utilities.

## 🏗️ Architecture

### Core Components

- **`main.py`** - Entry point and orchestration
- **`flow.py`** - Workflow engine and execution logic  
- **`nodes.py`** - Processing nodes for different operations
- **`utils/`** - Utility modules and LLM integration

### AI Integration Files

- **`.cursorrules`** - Cursor AI editor rules and preferences
- **`.clinerules`** - CLI-based AI tool configurations
- **`.goosehints`** - Goose AI assistant guidelines
- **`.windsurfrules`** - Windsurf AI development rules
- **`CLAUDE.md`** - Claude AI interaction guidelines
- **`GEMINI.md`** - Google Gemini AI guidelines

## 🚀 Getting Started

### Installation

```bash
git clone https://github.com/MattJonesIntel/PocketFlow.git
cd PocketFlow
pip install -r requirements.txt
```

### Basic Usage

```bash
# Generate a new utility script
python main.py

# Run with specific flow configuration
python main.py --config custom_flow.json

# Generate business operations tool
python main.py --template business-operations

# Generate automation utility
python main.py --template automation
```

## 📋 Template Categories

PocketFlow can generate templates for:

- **Media Tools**: Video/audio processing, subtitle manipulation
- **Business Operations**: Data analysis, Excel processing, reporting
- **Automation Tools**: File management, workflow automation
- **Coding Practice**: Algorithm implementations, ML exercises
- **Data Processing**: ETL pipelines, API integrations

## 🔧 Configuration

### AI Assistant Rules

Each AI tool has specific configuration files:

- **Cursor**: `.cursorrules` - IDE integration and code completion
- **CLI Tools**: `.clinerules` - Command-line AI tool behavior  
- **Goose**: `.goosehints` - Code generation and refactoring hints
- **Windsurf**: `.windsurfrules` - Development workflow automation
- **Claude**: `CLAUDE.md` - Conversation guidelines and context
- **Gemini**: `GEMINI.md` - Google AI integration patterns

### Workflow Customization

Edit `flow.py` to customize:
- Code generation patterns
- Template selection logic
- Output formatting and structure
- Integration with target repositories

## 📁 Integration with python-utilities

Generated code is designed to integrate seamlessly with structured repositories:

```bash
# Generate a business tool
python main.py --template business-operations

# Output automatically structured for:
# python-utilities/business-operations/new-tool.py
# python-utilities/business-operations/README.md (updated)
```

## 🛠️ Development

### Project Structure

```
PocketFlow/
├── main.py              # Entry point
├── flow.py              # Workflow engine
├── nodes.py             # Processing nodes
├── requirements.txt     # Dependencies
├── utils/               # Utility modules
│   ├── call_llm.py     # LLM integration
│   └── __init__.py     
├── docs/                # Documentation
│   └── design.md       # Architecture details
├── assets/              # Visual assets
│   └── banner.png      # Repository banner
└── .github/             # GitHub configuration
    └── copilot-instructions.md
```

### Contributing

1. Follow the AI assistant rules in the configuration files
2. Maintain template structure consistency
3. Test generated code with target repositories
4. Update documentation for new template types
5. Ensure AI integration guidelines are current

## 📖 Documentation

- **[Design Documentation](docs/design.md)** - Architecture and design decisions
- **[AI Integration Guide](CLAUDE.md)** - Working with AI assistants

## 🔗 Related Projects

- **[python-utilities](https://github.com/MattJonesIntel/python-utilities)** - Target repository for generated utilities
- **[Original Pocket Flow](https://github.com/The-Pocket/PocketFlow)** - Base framework inspiration
- **Intel Development Tools** - Corporate development standards

## 📄 License

MIT License - See LICENSE file for details

## 🤝 Support

For questions about PocketFlow or generated templates:
- Create an issue in this repository
- Review the AI assistant guidelines for your preferred tool
- Check the design documentation for architecture details

---

*PocketFlow: Transforming AI-generated code into production-ready utilities*