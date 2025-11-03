# Mixed Dependencies Test Repository

This repository combines multiple types of dependencies for comprehensive testing.

## Dependency Types

### 1. Submodules
- Local submodule: test-dependency-target (same org)
- External submodule: actions/checkout

### 2. GitHub Actions Workflows
- Reusable workflow from same org
- Actions from external repos (actions/checkout, etc.)

### 3. Package Dependencies
- npm packages (express, react, etc.)
- Go modules
- Python packages

## Purpose

This repository tests:
- Multiple dependency detection methods simultaneously
- Classification of local vs external dependencies across all types
- Batch planning scenarios with complex dependencies
- UI display of mixed dependency types

## Discovery Testing

When discovered, this repository should show:
- Total dependencies: 15+
- Local dependencies: 2+
- External dependencies: 13+
- By type: submodules, workflows, dependency_graph
