# Chart › Legend › Index

> **Category:** chart
> **Component Name:** `flux:chart.legend.index`

## Overview

Data visualization component for displaying charts and graphs.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `label` | `mixed` | `null` | Configuration for label |
| `field` | `mixed` | `null` | Configuration for field |
| `format` | `mixed` | `null` | Configuration for format |

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:chart.legend.index
/>
```

### Advanced Example

```blade
<flux:chart.legend.index
    label="value"
    field="value"
    format="value"
>
    Advanced content
</flux:chart.legend.index>
```

### With Livewire

```blade
<flux:chart.legend.index
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
- [Chart › Legend › Indicator](./legend-indicator.md)
- [Chart › Index](./index.md)
- [Chart › Area](./area.md)
- [Chart › Tooltip › Index](./tooltip-index.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features

---

*Generated on February 17, 2026*
