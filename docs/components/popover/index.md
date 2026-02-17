# Popover › Index

> **Category:** popover
> **Component Name:** `flux:popover.index`

## Overview

Floating overlay that appears relative to a trigger element.

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:popover.index
/>
```

### With Livewire

```blade
<flux:popover.index
    wire:model="property"
/>
```

## Accessibility

- Keyboard navigation support with proper focus management

## Styling

### Default Styling

The component uses Tailwind CSS classes for styling. Key styling features:

- **Dark mode support** - Automatically adapts to dark mode
- **Border radius** - Rounded corners for modern appearance
- **Shadows** - Depth and elevation effects

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Technical Notes

- Uses the `@blaze` directive for enhanced component features

---

*Generated on February 17, 2026*
