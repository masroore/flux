# Date picker › Selected

> **Category:** date-picker
> **Component Name:** `flux:date-picker.selected`

## Overview

Date picker input with calendar interface.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `placeholder` | `mixed` | `null` | Placeholder text when no value is selected |

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:date-picker.selected
    placeholder="Enter value"
/>
```

### With Livewire

```blade
<flux:date-picker.selected
    wire:model="property"
/>
```

## Accessibility

- Disabled states are properly communicated to assistive technologies
- Visual and functional disabled states

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

- [Date picker › Index](./index.md)
- [Date picker › Input](./input.md)
- [Date picker › Button](./button.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Contains `wire:ignore` regions for JavaScript library integration
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
