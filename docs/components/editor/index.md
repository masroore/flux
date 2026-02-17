# Editor › Index

> **Category:** editor
> **Component Name:** `flux:editor.index`

## Overview

Rich text editor with formatting toolbar.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `toolbar` | `mixed` | `null` | Toolbar configuration |
| `invalid` | `mixed` | `null` | Whether the component is in an invalid state |
| `variant` | `mixed` | `null` | Visual style variant of the component |
| `name` | `mixed` | `null` | Form field name attribute |

## Default Slot

This component accepts a default slot for its main content.

## Supported Attributes

- `wire:model`
- `disabled`

## Usage

### Basic Example

```blade
<flux:editor.index
    name="field_name"
/>
```

### Advanced Example

```blade
<flux:editor.index
    toolbar="value"
    invalid="value"
    variant="value"
>
    Advanced content
</flux:editor.index>
```

### With Livewire

```blade
<flux:editor.index
    wire:model="property"
/>
```

## Accessibility

- ARIA labels are properly set for screen readers
- Comprehensive ARIA attributes for accessibility
- Disabled states are properly communicated to assistive technologies
- Visual and functional disabled states

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
- [Editor › Spacer](./spacer.md)
- [Editor › Subscript](./subscript.md)
- [Editor › Styles](./styles.md)
- [Editor › Underline](./underline.md)

## Technical Notes

- Supports Livewire `wire:model` binding
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
