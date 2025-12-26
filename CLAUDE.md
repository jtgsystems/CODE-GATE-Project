# CLAUDE.md - CODE-GATE Project Documentation

## Project Overview

CODE-GATE is a meta-framework designed to enhance AI coding agents with advanced capabilities including long-term memory, strategic planning, self-correction, and reference intelligence. It is powered by Gemini CLI and builds upon lessons learned from leading autonomous agent architectures.

## Purpose

The CODE-GATE project serves as a comprehensive framework for building more capable and autonomous AI development agents by implementing:

1. **Long-term Memory**: Persistent project knowledge through `knowledge.md` files
2. **Strategic Planning**: Dynamic re-planning capabilities via the Conductor extension
3. **Self-Correction**: Critic loop for auditing plans before execution
4. **Reference Intelligence**: Curated library of system prompts from top AI engineering tools

## Project Structure

```
CODE-GATE-Project/
├── conductor-enhanced/     # Custom Gemini CLI extension (currently empty - planned implementation)
├── prompts/
│   └── reference/         # Gold Standard prompts from leading AI tools
│       ├── Cline_Prompt.txt      # Cline's system prompt
│       ├── Devin_DeepWiki.txt    # Devin's documentation system
│       └── Traycer_PlanMode.txt  # Traycer's planning mode
├── references/            # Architectural study materials
│   ├── AutoGPT/          # AutoGPT reference (empty placeholder)
│   ├── MetaGPT/          # MetaGPT reference (empty placeholder)
│   └── babyagi/          # BabyAGI reference (empty placeholder)
├── system_prompts_raw/   # Massive collection of system prompts (currently empty)
└── README.md             # Project overview and features
```

## Core Components

### 1. Conductor Extension (v2)

The Conductor is a custom Gemini CLI extension that implements several key commands:

- **/conductor:critic** - Audits your `plan.md` for potential risks and issues
- **/conductor:replan** - Handles major strategy shifts (e.g., "Switch to React")
- **/conductor:remember** - Saves constraints and decisions to `knowledge.md`
- **/conductor:prioritize** - Re-orders tasks based on urgency and dependencies

**Note**: The conductor-enhanced directory is currently a placeholder for future implementation.

### 2. Reference Prompts

The project includes curated system prompts from industry-leading AI coding assistants:

#### Cline Prompt
- Comprehensive tool use framework
- XML-based tool formatting
- Iterative step-by-step execution model
- Support for file operations, command execution, and browser automation
- Plan Mode vs Act Mode distinction

#### Devin DeepWiki
- Query-based codebase exploration
- Citation-based code references
- Structured answer format with notes
- Emphasis on precision and avoiding speculation
- Support for mermaid diagrams for explanation

#### Traycer Plan Mode
- Tech lead perspective for task breakdown
- Readonly codebase access focus
- High-level phase planning
- IDE-scoped development tasks
- Multi-tool usage optimization

### 3. Reference Architectures

Placeholder directories for studying autonomous agent implementations:
- **AutoGPT**: Goal-oriented autonomous agent
- **MetaGPT**: Multi-agent software development framework
- **BabyAGI**: Task-driven autonomous agent

### 4. System Prompts Collection

The `system_prompts_raw/` directory is intended to house a comprehensive collection from [x1xhlol's repository](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools).

## Key Concepts

### Long-term Memory
Projects maintain a `knowledge.md` file that persists:
- User preferences and constraints
- Architectural decisions
- Important patterns and conventions
- Lessons learned during development

### Strategic Planning
The Conductor enables:
- Breaking down complex tasks into phases
- Dynamic re-planning when requirements change
- Context-aware task prioritization
- Risk assessment before execution

### Self-Correction
The Critic loop provides:
- Pre-execution plan auditing
- Risk identification
- Alternative approach suggestions
- Validation of assumptions

### Reference Intelligence
Learning from best practices:
- Study of proven system prompts
- Analysis of successful agent architectures
- Pattern recognition across frameworks
- Implementation of battle-tested approaches

## Development Philosophy

CODE-GATE emphasizes:

1. **Iterative Development**: Step-by-step task execution with validation
2. **Context Awareness**: Deep understanding of project structure and conventions
3. **Intelligent Planning**: Breaking complex tasks into manageable phases
4. **Self-Improvement**: Learning from feedback and adjusting strategies
5. **Tool Mastery**: Effective use of available development tools

## Use Cases

This framework is designed for:

- Building complex software applications with AI assistance
- Maintaining large codebases with consistent patterns
- Implementing strategic refactoring across multiple files
- Learning from and adapting proven AI agent architectures
- Developing autonomous coding capabilities

## Technology Stack

- **Runtime**: Gemini CLI (Google's AI platform)
- **Extension System**: Custom Conductor implementation
- **Knowledge Format**: Markdown-based persistence
- **Reference Material**: System prompts and open-source agent architectures

## Current Status

The project is in its initial setup phase:
- Core directory structure established
- Reference prompts collected and documented
- Placeholder structures for future implementation
- Ready for Conductor extension development

## Future Development

Planned enhancements include:

1. **Conductor Implementation**: Full development of the Conductor extension with all planned commands
2. **Reference Repository Population**: Cloning and studying AutoGPT, MetaGPT, and BabyAGI
3. **System Prompts Collection**: Integration of comprehensive prompt library
4. **Knowledge Management**: Automated `knowledge.md` creation and maintenance
5. **Planning Tools**: Advanced task breakdown and prioritization algorithms
6. **Critic System**: Intelligent plan auditing and risk assessment

## Acknowledgements

This project builds upon and learns from:

- **System Prompts Collection**: [x1xhlol](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools)
- **Architectural References**: AutoGPT, MetaGPT, BabyAGI communities
- **AI Tool Developers**: Cline, Devin, Traycer teams for their innovative approaches

## Contributing

The CODE-GATE framework serves as a foundation for building more capable AI development agents. Future contributions could focus on:

- Implementing the Conductor extension commands
- Populating reference architecture studies
- Expanding the prompt library
- Developing additional meta-framework capabilities
- Sharing lessons learned and best practices

## License

(License information not specified in current repository)

---

**Generated on**: 2025-12-26
**Repository**: https://github.com/jtgsystems/CODE-GATE-Project
**Documentation by**: Claude (Anthropic)
