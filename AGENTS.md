# Reading List — Agent Instructions

## Naming Convention

All files in this repository follow the pattern:

```
YYYY-author-short-topic.pdf
```

- **YYYY**: Publication year (use `0000` if unknown/undated)
- **author**: Last name of first author, or organization name (e.g., `deepseek`, `nvidia`, `kimi`)
- **short-topic**: Lowercase, hyphen-separated summary of the subject (2-5 words)

Examples:
- `2025-hafner-dreamer4-scalable-world-models.pdf`
- `2024-wang-timexer-exogenous-forecasting.pdf`
- `0000-smith-dsp-ch18-fft-convolution.pdf`

## Index Maintenance

`INDEX.md` is the master index of all items in this reading list. When adding, removing, or renaming a file:

1. **Add/remove** the entry in the appropriate topic section of `INDEX.md`
2. **Use the naming convention** above for any new files
3. **Rename** files that don't follow the convention before adding them to the index
4. **Create a new section** in `INDEX.md` if no existing topic fits; keep sections alphabetical after the first natural grouping
5. **Link** entries using relative markdown links: `[filename](filename)`
6. Each entry gets a one-line description summarizing the paper's key contribution

## When the user adds a new paper

1. Read page 1-2 to determine year, author/org, and topic
2. Rename the file to match the naming convention
3. Write a one-line description of the paper's contribution
4. Add it to the correct section in `INDEX.md`
