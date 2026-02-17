# Pillbox › Variants › Default

> **Category:** pillbox
> **Component Name:** `flux:pillbox.variants.default`

## Overview

Multi-select component displaying selected items as pills.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `selectedSuffix` | `mixed` | `null` | Configuration for selectedSuffix |
| `placeholder` | `mixed` | `null` | Placeholder text when no value is selected |
| `searchable` | `mixed` | `null` | Whether the component is searchable |
| `clearable` | `mixed` | `null` | Whether the component shows a clear button |
| `invalid` | `mixed` | `null` | Whether the component is in an invalid state |
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
<flux:pillbox.variants.default
    placeholder="Enter value"
    name="field_name"
>
    Content here
</flux:pillbox.variants.default>
```

### Advanced Example

```blade
<flux:pillbox.variants.default
    selectedSuffix="value"
    placeholder="value"
    searchable="value"
    clearable="value"
>
    Advanced content
</flux:pillbox.variants.default>
```

### With Livewire

```blade
<flux:pillbox.variants.default
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

- [Pillbox › Index](./index.md)
- [Pillbox › Options](./options.md)
- [Pillbox › Variants › Combobox](./variants-combobox.md)
- [Pillbox › Trigger](./trigger.md)
- [Pillbox › Option](./option.md)

## Technical Notes

- Supports Livewire `wire:model` binding
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
