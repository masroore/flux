# Pillbox › Input

> **Category:** pillbox
> **Component Name:** `flux:pillbox.input`

## Overview

Multi-select component displaying selected items as pills.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `placeholder` | `mixed` | `null` | Placeholder text when no value is selected |
| `invalid` | `mixed` | `null` | Whether the component is in an invalid state |

## Supported Attributes

- `wire:model`
- `disabled`

## Usage

### Basic Example

```blade
<flux:pillbox.input
    placeholder="Enter value"
/>
```

### With Livewire

```blade
<flux:pillbox.input
    wire:model="property"
/>
```

## Accessibility

- Comprehensive ARIA attributes for accessibility
- Disabled states are properly communicated to assistive technologies

## Styling

### Default Styling

The component uses Tailwind CSS classes for styling. Key styling features:

- **Dark mode support** - Automatically adapts to dark mode
- **Disabled states** - Visual indication when disabled

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

- Supports Livewire `wire:model` binding

---

*Generated on February 17, 2026*
