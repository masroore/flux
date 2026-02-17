# Editor › Bold

> **Category:** editor
> **Component Name:** `flux:editor.bold`

## Overview

Rich text editor with formatting toolbar.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `kbd` | `string` | `'⌘B'` | Configuration for kbd |

## Usage

### Basic Example

```blade
<flux:editor.bold
/>
```

### With Livewire

```blade
<flux:editor.bold
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

- [Editor › Superscript](./superscript.md)
- [Editor › Index](./index.md)
- [Editor › Spacer](./spacer.md)
- [Editor › Subscript](./subscript.md)
- [Editor › Styles](./styles.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features

---

*Generated on February 17, 2026*
