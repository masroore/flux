# Chart › Area

> **Category:** chart
> **Component Name:** `flux:chart.area`

## Overview

Data visualization component for displaying charts and graphs.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `field` | `string` | `'value'` | Configuration for field |

## Inherited Props (via @aware)

These props are inherited from parent components:

- `field`

## Usage

### Basic Example

```blade
<flux:chart.area
/>
```

### With Livewire

```blade
<flux:chart.area
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
- [Chart › Tooltip › Index](./tooltip-index.md)

## Technical Notes

- Standard Blade component implementation

---

*Generated on February 17, 2026*
