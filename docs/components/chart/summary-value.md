# Chart › Summary › Value

> **Category:** chart
> **Component Name:** `flux:chart.summary.value`

## Overview

Data visualization component for displaying charts and graphs.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `field` | `mixed` | `null` | Configuration for field |
| `format` | `mixed` | `null` | Configuration for format |
| `fallback` | `mixed` | `null` | Configuration for fallback |

## Usage

### Basic Example

```blade
<flux:chart.summary.value
/>
```

### Advanced Example

```blade
<flux:chart.summary.value
    field="value"
    format="value"
    fallback="value"
>
    Advanced content
</flux:chart.summary.value>
```

### With Livewire

```blade
<flux:chart.summary.value
    wire:model="property"
/>
```

## Accessibility

- Component follows standard HTML accessibility practices
- Keyboard navigation supported where applicable

## Styling

### Default Styling

The component uses Tailwind CSS classes for styling. Key styling features:


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

- Uses the `@blaze` directive for enhanced component features

---

*Generated on February 17, 2026*
