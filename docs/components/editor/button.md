# Editor › Button

> **Category:** editor
> **Component Name:** `flux:editor.button`

## Overview

Rich text editor with formatting toolbar.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `iconVariant` | `mixed` | `null` | Configuration for iconVariant |
| `icon` | `mixed` | `null` | Configuration for icon |

## Default Slot

This component accepts a default slot for its main content.

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:editor.button
/>
```

### With Livewire

```blade
<flux:editor.button
    wire:model="property"
/>
```

## Accessibility

- Disabled states are properly communicated to assistive technologies

## Styling

### Default Styling

The component uses Tailwind CSS classes for styling. Key styling features:

- **Dark mode support** - Automatically adapts to dark mode
- **Border radius** - Rounded corners for modern appearance
- **Hover states** - Interactive feedback on hover
- **Disabled states** - Visual indication when disabled

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
