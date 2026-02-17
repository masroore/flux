# Editor › Superscript

> **Category:** editor
> **Component Name:** `flux:editor.superscript`

## Overview

Rich text editor with formatting toolbar.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `kbd` | `mixed` | `null` | Configuration for kbd |

## Usage

### Basic Example

```blade
<flux:editor.superscript
/>
```

### With Livewire

```blade
<flux:editor.superscript
    wire:model="property"
/>
```

## Accessibility

- Comprehensive ARIA attributes for accessibility

## Styling

### Default Styling

The component uses Tailwind CSS classes for styling. Key styling features:


### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [Editor › Index](./index.md)
- [Editor › Spacer](./spacer.md)
- [Editor › Subscript](./subscript.md)
- [Editor › Styles](./styles.md)
- [Editor › Underline](./underline.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features

---

*Generated on February 17, 2026*
