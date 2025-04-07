# Coding Exercise: YAML Summariser

Welcome to this simple coding exercise!

## Purpose

You are given a small collection of YAML files (`configs/` folder). Each file contains metadata about a service or environment. Your goal is to write a script (in any language you prefer) that:

1. Iterates over all YAML files in the `configs/` folder.
2. Searches for specific keys (e.g. `environment:` and `version:`).
3. Extracts the values of these keys.
4. Produces a summary of how many times each unique value appears.

**Example**:

If the `configs/` folder has three files with these values:
- `environment: "production"`
- `environment: "staging"`
- `version: "1.2"`
- `version: "2.0"`

Your script might output something like:

