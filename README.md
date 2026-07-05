# @comfortcss/grid

Stop writing `grid-template-columns: repeat(3, 1fr)` and `gap: `1rem` over and over. This package gives you simple, composable classes for everything CSS Grid - from containers to placement, alignment, and auto-flow.

## Installation

```bash
npm install @comfortcss/grid @comfortcss/tokens
```

This package expects `@comfortcss/tokens` for spacing values (it’s a peer dependency).

## Usage

Add this to your main CSS file:

```css
@import '~@comfortcss/tokens';
@import '~@comfortcss/grid';
```

Then use classes in your HTML.

## What’s inside

| Class | Description|
|-------|------------|
| `.grid` | Block-level grid container |
| `.inline-grid` | Inline-level grid container |

### Container

## Dependencies

- [`@comfortcss/tokens`](https://github.com/ComfortCSS/tokens)

## License

[MIT](LICENSE)
