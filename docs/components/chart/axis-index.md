# Chart › Axis › Index

> **Category:** chart
> **Component Name:** `flux:chart.axis.index`

## Overview

Data visualization component for displaying charts and graphs.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `axis` | `string` | `'x'` | Configuration for axis |
| `format` | `mixed` | `null` | Configuration for format |
| `field` | `string` | `'index'` | Configuration for field |
| `position` | `mixed` | `null` | Position of the floating element |
| `tickValues` | `mixed` | `null` | Configuration for tickValues |

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:chart.axis.index
/>
```

### Advanced Example

```blade
<flux:chart.axis.index
    axis="value"
    format="value"
    field="value"
    position="value"
>
    Advanced content
</flux:chart.axis.index>
```

### With Livewire

```blade
<flux:chart.axis.index
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
