# Chart › Index

> **Category:** chart
> **Component Name:** `flux:chart.index`

## Overview

Data visualization component for displaying charts and graphs.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `tooltip` | `mixed` | `null` | Configuration for tooltip |
| `summary` | `mixed` | `null` | Configuration for summary |
| `value` | `mixed` | `null` | Current value of the component |
| `svg` | `mixed` | `null` | Configuration for svg |

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:chart.index
/>
```

### Advanced Example

```blade
<flux:chart.index
    tooltip="value"
    summary="value"
    value="value"
    svg="value"
>
    Advanced content
</flux:chart.index>
```

### With Livewire

```blade
<flux:chart.index
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
- [Chart › Area](./area.md)
- [Chart › Tooltip › Index](./tooltip-index.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Contains `wire:ignore` regions for JavaScript library integration
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
