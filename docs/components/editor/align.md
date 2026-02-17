# Editor › Align

> **Category:** editor
> **Component Name:** `flux:editor.align`

## Overview

Rich text editor with formatting toolbar.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `kbd` | `mixed` | `null` | Configuration for kbd |

## Usage

### Basic Example

```blade
<flux:editor.align
/>
```

### With Livewire

```blade
<flux:editor.align
    wire:model="property"
/>
```

## Accessibility

- Comprehensive ARIA attributes for accessibility

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


## Related Components

- [Editor › Superscript](./superscript.md)
- [Editor › Index](./index.md)
- [Editor › Spacer](./spacer.md)
- [Editor › Subscript](./subscript.md)
- [Editor › Styles](./styles.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
