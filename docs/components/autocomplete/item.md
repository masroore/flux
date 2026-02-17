# Autocomplete › Item

> **Category:** autocomplete
> **Component Name:** `flux:autocomplete.item`

## Overview

Input field with auto-completion suggestions.

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:autocomplete.item
/>
```

### With Livewire

```blade
<flux:autocomplete.item
    wire:model="property"
/>
```

## Accessibility

- Component follows standard HTML accessibility practices
- Keyboard navigation supported where applicable

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

- [Autocomplete › Index](./index.md)
- [Autocomplete › Items](./items.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
