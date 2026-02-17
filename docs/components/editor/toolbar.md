# Editor › Toolbar

> **Category:** editor
> **Component Name:** `flux:editor.toolbar`

## Overview

Rich text editor with formatting toolbar.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `items` | `mixed` | `null` | Configuration for items |
| `variant` | `mixed` | `null` | Visual style variant of the component |

## Inherited Props (via @aware)

These props are inherited from parent components:

- `variant`

## Slots

| Slot | Required | Description |
|------|----------|-------------|
| `item` | No | Custom item content |

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:editor.toolbar
>
    Content here
</flux:editor.toolbar>
```

### With Livewire

```blade
<flux:editor.toolbar
    wire:model="property"
/>
```

## Accessibility

- ARIA labels are properly set for screen readers
- Comprehensive ARIA attributes for accessibility

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

- [Editor › Superscript](./superscript.md)
- [Editor › Index](./index.md)
- [Editor › Spacer](./spacer.md)
- [Editor › Subscript](./subscript.md)
- [Editor › Styles](./styles.md)

## Technical Notes

- Contains `wire:ignore` regions for JavaScript library integration
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
