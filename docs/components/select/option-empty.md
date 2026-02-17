# Select › Option › Empty

> **Category:** select
> **Component Name:** `flux:select.option.empty`

## Overview

Dropdown select component with search and filtering.

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:select.option.empty
/>
```

### With Livewire

```blade
<flux:select.option.empty
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

- [Select › Options](./options.md)
- [Select › Variants › Custom](./variants-custom.md)
- [Select › Variants › Combobox](./variants-combobox.md)
- [Select › Variants › Listbox](./variants-listbox.md)
- [Select › Indicator › Index](./indicator-index.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Contains `wire:ignore` regions for JavaScript library integration
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
