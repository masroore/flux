# Editor › Separator

> **Category:** editor
> **Component Name:** `flux:editor.separator`

## Overview

Rich text editor with formatting toolbar.

## Usage

### Basic Example

```blade
<flux:editor.separator
/>
```

### With Livewire

```blade
<flux:editor.separator
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

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [Editor › Superscript](./superscript.md)
- [Editor › Index](./index.md)
- [Editor › Spacer](./spacer.md)
- [Editor › Subscript](./subscript.md)
- [Editor › Styles](./styles.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features

---

*Generated on February 17, 2026*
