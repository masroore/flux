# Select › Variants › Combobox

> **Category:** select
> **Component Name:** `flux:select.variants.combobox`

## Overview

Dropdown select component with search and filtering.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `placeholder` | `mixed` | `null` | Placeholder text when no value is selected |
| `searchable` | `mixed` | `null` | Whether the component is searchable |
| `clearable` | `mixed` | `null` | Whether the component shows a clear button |
| `multiple` | `mixed` | `null` | Configuration for multiple |
| `invalid` | `mixed` | `null` | Whether the component is in an invalid state |
| `empty` | `mixed` | `null` | Configuration for empty |
| `input` | `mixed` | `null` | Configuration for input |
| `size` | `mixed` | `null` | Size variant of the component |
| `name` | `mixed` | `null` | Form field name attribute |

## Default Slot

This component accepts a default slot for its main content.

## Supported Attributes

- `wire:model`

## Usage

### Basic Example

```blade
<flux:select.variants.combobox
    placeholder="Enter value"
    name="field_name"
/>
```

### Advanced Example

```blade
<flux:select.variants.combobox
    placeholder="value"
    searchable="value"
    clearable="value"
    multiple="value"
>
    Advanced content
</flux:select.variants.combobox>
```

### With Livewire

```blade
<flux:select.variants.combobox
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
- [Select › Variants › Listbox](./variants-listbox.md)
- [Select › Indicator › Index](./indicator-index.md)
- [Select › Indicator › Variants › Check](./indicator-variants-check.md)

## Technical Notes

- Supports Livewire `wire:model` binding
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
