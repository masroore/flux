# Select › Selected

> **Category:** select
> **Component Name:** `flux:select.selected`

## Overview

Dropdown select component with search and filtering.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `placeholder` | `mixed` | `null` | Placeholder text when no value is selected |
| `suffix` | `mixed` | `null` | Configuration for suffix |
| `max` | `number` | `1` | Configuration for max |

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:select.selected
    placeholder="Enter value"
/>
```

### Advanced Example

```blade
<flux:select.selected
    placeholder="value"
    suffix="value"
    max="value"
>
    Advanced content
</flux:select.selected>
```

### With Livewire

```blade
<flux:select.selected
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

- [Select › Options](./options.md)
- [Select › Variants › Custom](./variants-custom.md)
- [Select › Variants › Combobox](./variants-combobox.md)
- [Select › Variants › Listbox](./variants-listbox.md)
- [Select › Indicator › Index](./indicator-index.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Contains `wire:ignore` regions for JavaScript library integration
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
