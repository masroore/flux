# Toast › Group

> **Category:** toast
> **Component Name:** `flux:toast.group`

## Overview

Notification toast messages.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `position` | `string` | `'bottom end'` | Position of the floating element |
| `expanded` | `boolean` | `false` | Whether the component is initially expanded |

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:toast.group
/>
```

### With Livewire

```blade
<flux:toast.group
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

- [Toast › Index](./index.md)

## Technical Notes

- Contains `wire:ignore` regions for JavaScript library integration
- Uses Alpine.js for reactive behavior
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
