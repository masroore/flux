# Select › Variants › Custom

> **Category:** select
> **Component Name:** `flux:select.variants.custom`

## Overview

Dropdown select component with search and filtering.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `invalid` | `mixed` | `null` | Whether the component is in an invalid state |
| `clear` | `mixed` | `null` | Configuration for clear |
| `close` | `mixed` | `null` | Configuration for close |
| `size` | `mixed` | `null` | Size variant of the component |
| `name` | `mixed` | `null` | Form field name attribute |

## Supported Attributes

- `wire:model`

## Usage

### Basic Example

```blade
<flux:select.variants.custom
    name="field_name"
/>
```

### Advanced Example

```blade
<flux:select.variants.custom
    invalid="value"
    clear="value"
    close="value"
    size="value"
>
    Advanced content
</flux:select.variants.custom>
```

### With Livewire

```blade
<flux:select.variants.custom
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
- [Select › Variants › Combobox](./variants-combobox.md)
- [Select › Variants › Listbox](./variants-listbox.md)
- [Select › Indicator › Index](./indicator-index.md)
- [Select › Indicator › Variants › Check](./indicator-variants-check.md)

## Technical Notes

- Supports Livewire `wire:model` binding
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
