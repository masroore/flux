# Select › Variants › Listbox

> **Category:** select
> **Component Name:** `flux:select.variants.listbox`

## Overview

Dropdown select component with search and filtering.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `selectedSuffix` | `mixed` | `null` | Configuration for selectedSuffix |
| `placeholder` | `mixed` | `null` | Placeholder text when no value is selected |
| `searchable` | `mixed` | `null` | Whether the component is searchable |
| `clearable` | `mixed` | `null` | Whether the component shows a clear button |
| `invalid` | `mixed` | `null` | Whether the component is in an invalid state |
| `button` | `mixed` | `null` | Configuration for button |
| `trigger` | `mixed` | `null` | Configuration for trigger |
| `search` | `mixed` | `null` | Configuration for search |
| `empty` | `mixed` | `null` | Configuration for empty |
| `clear` | `mixed` | `null` | Configuration for clear |
| `close` | `mixed` | `null` | Configuration for close |
| `name` | `mixed` | `null` | Form field name attribute |
| `size` | `mixed` | `null` | Size variant of the component |

## Slots

| Slot | Required | Description |
|------|----------|-------------|
| `search` | No | Custom search input |
| `empty` | No | Content shown when no items are available |

## Default Slot

This component accepts a default slot for its main content.

## Supported Attributes

- `wire:model`

## Usage

### Basic Example

```blade
<flux:select.variants.listbox
    placeholder="Enter value"
    name="field_name"
>
    Content here
</flux:select.variants.listbox>
```

### Advanced Example

```blade
<flux:select.variants.listbox
    selectedSuffix="value"
    placeholder="value"
    searchable="value"
    clearable="value"
>
    Advanced content
</flux:select.variants.listbox>
```

### With Livewire

```blade
<flux:select.variants.listbox
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
- [Select › Indicator › Index](./indicator-index.md)
- [Select › Indicator › Variants › Check](./indicator-variants-check.md)

## Technical Notes

- Supports Livewire `wire:model` binding
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
