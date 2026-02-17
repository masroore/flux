# Pillbox › Option

> **Category:** pillbox
> **Component Name:** `flux:pillbox.option`

## Overview

Multi-select component displaying selected items as pills.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `filterable` | `mixed` | `null` | Configuration for filterable |
| `loading` | `mixed` | `null` | Configuration for loading |
| `label` | `mixed` | `null` | Configuration for label |
| `value` | `mixed` | `null` | Current value of the component |

## Supported Attributes

- `wire:click`
- `disabled`

## Usage

### Basic Example

```blade
<flux:pillbox.option
/>
```

### Advanced Example

```blade
<flux:pillbox.option
    filterable="value"
    loading="value"
    label="value"
    value="value"
>
    Advanced content
</flux:pillbox.option>
```

### With Livewire

```blade
<flux:pillbox.option
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

- [Pillbox › Index](./index.md)
- [Pillbox › Options](./options.md)
- [Pillbox › Variants › Combobox](./variants-combobox.md)
- [Pillbox › Variants › Default](./variants-default.md)
- [Pillbox › Trigger](./trigger.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
