# Chart › Bar

> **Category:** chart
> **Component Name:** `flux:chart.bar`

## Overview

Data visualization component for displaying charts and graphs.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `minHeight` | `mixed` | `null` | Configuration for minHeight |
| `field` | `string` | `'value'` | Configuration for field |
| `radius` | `mixed` | `null` | Configuration for radius |
| `width` | `mixed` | `null` | Configuration for width |

## Usage

### Basic Example

```blade
<flux:chart.bar
/>
```

### Advanced Example

```blade
<flux:chart.bar
    minHeight="value"
    field="value"
    radius="value"
    width="value"
>
    Advanced content
</flux:chart.bar>
```

### With Livewire

```blade
<flux:chart.bar
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

- [Chart › Legend › Index](./legend-index.md)
- [Chart › Legend › Indicator](./legend-indicator.md)
- [Chart › Index](./index.md)
- [Chart › Area](./area.md)
- [Chart › Tooltip › Index](./tooltip-index.md)

## Technical Notes

- Standard Blade component implementation

---

*Generated on February 17, 2026*
