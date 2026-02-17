# Select › Option › Variants › Custom

> **Category:** select
> **Component Name:** `flux:select.option.variants.custom`

## Overview

Dropdown select component with search and filtering.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `filterable` | `mixed` | `null` | Configuration for filterable |
| `indicator` | `mixed` | `null` | Configuration for indicator |
| `loading` | `mixed` | `null` | Configuration for loading |
| `label` | `mixed` | `null` | Configuration for label |
| `value` | `mixed` | `null` | Current value of the component |

## Inherited Props (via @aware)

These props are inherited from parent components:

- `indicator`

## Supported Attributes

- `wire:click`
- `disabled`

## Usage

### Basic Example

```blade
<flux:select.option.variants.custom
/>
```

### Advanced Example

```blade
<flux:select.option.variants.custom
    filterable="value"
    indicator="value"
    loading="value"
    label="value"
>
    Advanced content
</flux:select.option.variants.custom>
```

### With Livewire

```blade
<flux:select.option.variants.custom
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
- **Border radius** - Rounded corners for modern appearance

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

- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
