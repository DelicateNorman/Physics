# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a Chinese Physics Education Repository containing laboratory experiment documentation, assessment materials, and teaching resources for university-level physics courses. All content is in Chinese and follows academic formatting standards.

## Repository Structure

The repository uses a three-tier hierarchical organization:

- **`document/`** - Formal experiment guides, teaching materials, and theoretical background
- **`paper/`** - Assessment materials, exam questions with detailed solutions and explanations
- **`原文件/`** - Original supplementary files (PDFs, PPTs, DOCs) for reference

## Key Experiments Covered

1. **声速与光速测量** (Sound and Light Speed Measurement)
2. **太阳能电池特性** (Solar Cell Characteristics)
3. **巨磁电阻** (Giant Magnetoresistance)
4. **核磁共振** (Nuclear Magnetic Resonance)
5. **落球法测粘滞系数** (Viscosity Measurement via Ball Bearing)
6. **迈克尔逊干涉仪** (Michelson Interferometer)

## Content Architecture

**Learning Flow**: Theory → Procedure → Assessment → Reference
- Learning materials in `document/` provide theoretical principles and experimental procedures
- Assessment materials in `paper/` include detailed explanations, formulas, and problem-solving approaches
- Original files in `原文件/` serve as supplementary visual and reference materials

**Content Patterns**:
- Mathematical formulas and experimental diagrams embedded via external CDN links
- Multiple versions of some experiments (e.g., different teaching approaches)
- Comprehensive assessment solutions with step-by-step explanations
- Academic formatting following Chinese university standards

## Development Workflow

**No Build System**: This is a static documentation repository requiring no compilation or dependency management.

**Content Management**:
- Edit Markdown files directly with any text editor
- Maintain consistent Chinese academic formatting
- Ensure mathematical formulas and diagrams are properly referenced
- Cross-reference related materials across the three directories

**Git Operations**:
- Repository is already initialized with basic structure
- Use standard git workflow for content changes
- Permissions configured for git remote operations in `.claude/settings.local.json`

## Working with Content

**When editing experiment documentation**:
- Maintain theoretical background → experimental procedure → data analysis structure
- Include mathematical formulas with proper LaTeX-style notation
- Reference external images via CDN links consistently
- Follow Chinese academic writing conventions

**When creating assessment materials**:
- Provide comprehensive solutions with step-by-step explanations
- Include relevant formulas and theoretical background
- Structure questions to test both conceptual understanding and practical application

**File Naming**:
- Use descriptive Chinese names following existing patterns
- Maintain consistency between related files (e.g., experiment guide and corresponding exam questions)
- Include version distinctions when multiple approaches exist (e.g., different teaching methods)