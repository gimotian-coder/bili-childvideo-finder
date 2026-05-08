# Bilibili Kids Animation Finder

Help parents, teachers, and early childhood education institutions quickly find age-appropriate cartoons and animations on Bilibili (B站).

[中文版](README_zh.md)

## Features

- Age-based recommendations — Supports 3-5 years (preschool), 6-8 years (lower primary), 9-12 years (upper primary)
- Multi-language support — Chinese, English, Bilingual, Korean, and more
- Content safety filtering — Automatically excludes violent, horror, or adult-oriented content for child-safe viewing
- Video availability filtering — Evaluates video quality, free vs paid, and content authenticity
- Smart ranking — Sorts by favorites count, play count, creator authority for top recommendations
- Quantity control — Supports custom recommendation count (default up to 8 items) to avoid information overload
- Structured output — Recommendations include Bilibili links, age suitability, reasons, and usage tips

## Use Cases

- Find age-appropriate cartoons for your kids
- Prepare video materials for parent-child activities, classroom teaching, or training courses
- Check whether a specific animation is suitable for your child

## How to Use

Simply type your request in QoderWork, for example:

```
Find me math启蒙 animations suitable for a 5-year-old, in Chinese, recommend around 5
```

```
I need some English启蒙 animations for an 8-year-old, bilingual would be great
```

```
Find science科普 animations for 9-12 year olds for a parent-child education course
```

## Core Workflow

1. **Understand Needs** — Clarify age range, language type, and quantity
2. **Build Search Strategy** — Use Bilibili search keyword combinations to precisely locate content
3. **Content Safety Filter** — Exclude content unsuitable for children
4. **Video Availability Filter** — Evaluate video quality, free vs paid, and content authenticity
5. **Refine & Rank** — Sort by favorites count, play count, and other metrics for top recommendations (up to 8 items)
6. **Output Recommendations** — Generate complete recommendations with links, reasons, and usage tips

## File Structure

```
bilibili-kids-animation-finder/
├── SKILL.md              # Core instruction file
├── reference.md          # Detailed reference (age characteristics, keyword library)
├── examples.md           # Recommendation list examples
├── README.md             # English documentation
└── README_zh.md          # Chinese documentation
```

## Example Output

The skill generates structured recommendations like this:

**Requirements Summary**

| Item | Content |
|------|---------|
| Target Age | 5 years (Preschool) |
| Language | Chinese |
| Recommended | 5 items |

**Recommendation List**

**1. Numberblocks (Chinese Version)**

| Item | Content |
|------|---------|
| Suitable Age | 3-6 years |
| Episode Length | 5 minutes |
| Why Recommended | BBC production, uses personified number characters to visualize abstract math concepts |
| Content Highlights | Each episode focuses on one number or math concept, with catchy math songs |
| Parent/Teacher Tips | Watch Chinese version first to build understanding, then transition to English |

## License

MIT License
