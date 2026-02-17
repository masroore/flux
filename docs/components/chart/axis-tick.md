# Chart › Axis › Tick

> **Category:** chart
> **Component Name:** `flux:chart.axis.tick`

## Overview

Data visualization component for displaying charts and graphs.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `format` | `mixed` | `null` | Configuration for format |

## Inherited Props (via @aware)

These props are inherited from parent components:

- `axis`
- `x`
- `position`

## Usage

### Basic Example

```blade
<flux:chart.axis.tick
/>
```

### With Livewire

```blade
<flux:chart.axis.tick
    wire:model="property"
/>
```

## Accessibility

- Component follows standard HTML accessibility practices
- Keyboard navigation supported where applicable

## Styling

### Default Styling

The component uses Tailwind CSS classes for styling. Key styling features:

- **Dark mode support** - Automatically adapts to dark mode

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [Chart › Bar](./bar.md)
- [Chart › Legend › Index](./legend-index.md)
- [Chart › Legend › Indicator](./legend-indicator.md)
- [Chart › Index](./index.md)
- [Chart › Area](./area.md)

## Technical Notes

- Standard Blade component implementation

---

*Generated on February 17, 2026*
