# Select › Indicator › Variants › Checkbox

> **Category:** select
> **Component Name:** `flux:select.indicator.variants.checkbox`

## Overview

Dropdown select component with search and filtering.

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:select.indicator.variants.checkbox
/>
```

### With Livewire

```blade
<flux:select.indicator.variants.checkbox
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
- **Hover states** - Interactive feedback on hover

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
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
