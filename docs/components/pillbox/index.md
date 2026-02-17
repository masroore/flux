# Pillbox › Index

> **Category:** pillbox
> **Component Name:** `flux:pillbox.index`

## Overview

Multi-select component displaying selected items as pills.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `variant` | `string` | `'default'` | Visual style variant of the component |

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:pillbox.index
/>
```

### With Livewire

```blade
<flux:pillbox.index
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

- [Pillbox › Options](./options.md)
- [Pillbox › Variants › Combobox](./variants-combobox.md)
- [Pillbox › Variants › Default](./variants-default.md)
- [Pillbox › Trigger](./trigger.md)
- [Pillbox › Option](./option.md)

## Technical Notes

- Standard Blade component implementation

---

*Generated on February 17, 2026*
