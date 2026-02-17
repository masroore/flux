# Select › Indicator › Index

> **Category:** select
> **Component Name:** `flux:select.indicator.index`

## Overview

Dropdown select component with search and filtering.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `variant` | `string` | `'check'` | Visual style variant of the component |

## Inherited Props (via @aware)

These props are inherited from parent components:

- `variant`

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:select.indicator.index
/>
```

### With Livewire

```blade
<flux:select.indicator.index
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

- [Select › Options](./options.md)
- [Select › Variants › Custom](./variants-custom.md)
- [Select › Variants › Combobox](./variants-combobox.md)
- [Select › Variants › Listbox](./variants-listbox.md)
- [Select › Indicator › Variants › Check](./indicator-variants-check.md)

## Technical Notes

- Standard Blade component implementation

---

*Generated on February 17, 2026*
