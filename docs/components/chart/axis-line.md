# Chart › Axis › Line

> **Category:** chart
> **Component Name:** `flux:chart.axis.line`

## Overview

Data visualization component for displaying charts and graphs.

## Inherited Props (via @aware)

These props are inherited from parent components:

- `axis`
- `x`

## Usage

### Basic Example

```blade
<flux:chart.axis.line
/>
```

### With Livewire

```blade
<flux:chart.axis.line
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
