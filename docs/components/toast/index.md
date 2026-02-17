# Toast › Index

> **Category:** toast
> **Component Name:** `flux:toast.index`

## Overview

Notification toast messages.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `position` | `string` | `'bottom end'` | Position of the floating element |

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:toast.index
/>
```

### With Livewire

```blade
<flux:toast.index
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
- **Border radius** - Rounded corners for modern appearance
- **Shadows** - Depth and elevation effects
- **Hover states** - Interactive feedback on hover
- **Disabled states** - Visual indication when disabled

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [Toast › Group](./group.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Contains `wire:ignore` regions for JavaScript library integration
- Uses Alpine.js for reactive behavior
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
