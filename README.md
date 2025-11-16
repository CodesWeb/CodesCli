# CodesCli

A multi-provider AI programming assistant with event-driven architecture.

## Features

- 🤖 **Multi-Provider Support**: Anthropic Claude & Google Gemini
- 🧠 **Intelligent Task Classification**: Auto-categorize tasks for optimal model selection
- 🛠️ **Rich Tool Set**: 7 built-in tools (Read, Write, Edit, Glob, Grep, Bash, TodoWrite)
- 🚀 **Pluggable Capabilities**: Caching, Warmup, Thinking, Streaming
- 📊 **Full Observability**: Real-time task classification and tool execution visualization
- 💰 **Cost Optimization**: Smart model scheduling reduces costs by 80%+

## Installation

```bash
npm install -g codescli
```

## Usage

After installation, you can start codescli using the global command:

```bash
codes
```

## Configuration

Create a `.env` file in your working directory with the following variables:

```bash
# Provider selection (anthropic or gemini)
PROVIDER=gemini

# API Keys
ANTHROPIC_API_KEY=your_anthropic_api_key
GEMINI_API_KEY=your_gemini_api_key

# Model configuration
MODEL=gemini-2.5-flash
FAST_MODEL=gemini-2.5-flash
POWERFUL_MODEL=gemini-2.5-pro
MAX_TOKENS=4096

# Feature toggles
ENABLE_CACHE=true
ENABLE_WARMUP=true
ENABLE_THINKING=true
ENABLE_STREAMING=true
ENABLE_MODEL_SCHEDULING=true
```

## Commands

- `/help` - Show help
- `/stats` - Show statistics
- `/clear` - Clear screen
- `/exit` or `/quit` - Exit application

## Supported Models

### Anthropic Claude
- claude-sonnet-4-5
- claude-haiku-4-5
- claude-opus

### Google Gemini
- gemini-2.5-pro
- gemini-2.5-flash
- gemini-2.0-flash

## License

ISC

## Repository

https://github.com/CodesWeb/CodesCli.git
