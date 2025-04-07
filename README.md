# Coding Exercise: YAML Summariser

Welcome to this simple coding exercise!

## Purpose

You are given a small collection of YAML files (in the `configs/` folder). Each file contains metadata about a service or environment. **Your task** is to write a script (in any language) that:

1. Iterates over all `.yaml` files in `configs/`.
2. Searches for specific keys (`environment:` and `version:`).
3. Extracts the values of these keys.
4. Produces a summary of how many times each unique value appears.

**Example**:

If the `configs/` folder has these values:
- `environment: "production"`
- `environment: "staging"`
- `version: "1.2"`
- `version: "2.0"`

You might output:

```bash
```
Environments found:
- production: 1
- staging: 2

Versions found:
- 1.2: 2
- 2.0: 1
```
```


## Reliability & Testing

Our CTO has emphasised that this solution should “work most of the time,” so it’s important to think about **how you will validate** the results. Please consider:

- **Edge Cases**: Missing keys, empty YAML files, malformed lines, etc.
- **Testing Approach**:
  - Simple manual tests to confirm correct behaviour.
  - Optional: Automated tests (e.g., using a testing framework in your chosen language).

**You don’t need to write extensive test suites**, but please do think about the scenarios you’d test to ensure reliability.

## Requirements

- String-based parsing is acceptable. **A full YAML parser** is **not** strictly required.
- Handle missing `environment:` or `version:` gracefully.
- Summarise results in a readable way.

## Timing

We aim for about **30 minutes** of coding time. We aren’t expecting polished production code, but we do want to see how you approach the problem, handle pressure, and think about testing for correctness.

## Instructions

1. Clone or download this repository.
2. Explore the files in the `configs/` folder.
3. Write a small script that accomplishes the goals above.
4. Think about how to ensure it “works most of the time” and potentially test with different scenarios.
5. Show/describe your output.

## Next Steps

Once you’ve finished:

- Discuss how reliable you believe your solution is for typical YAML files.
- Mention any tests you used to verify the script works as expected.
- Describe any improvements or additional features you’d add if you had more time.

Good luck, and have fun!

