# File item › Index

> **Category:** file-item
> **Component Name:** `flux:file-item.index`

## Overview

Individual file item display with metadata.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `icon` | `string` | `'document'` | Configuration for icon |
| `invalid` | `boolean` | `false` | Whether the component is in an invalid state |
| `actions` | `mixed` | `null` | Configuration for actions |
| `heading` | `mixed` | `null` | Configuration for heading |
| `inline` | `boolean` | `false` | Configuration for inline |
| `image` | `mixed` | `null` | Configuration for image |
| `text` | `mixed` | `null` | Configuration for text |
| `size` | `mixed` | `null` | Size variant of the component |

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:file-item.index
/>
```

### Advanced Example

```blade
<flux:file-item.index
    icon="value"
    invalid="value"
    actions="value"
    heading="value"
>
    Advanced content
</flux:file-item.index>
```

### With Livewire

```blade
<flux:file-item.index
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
- **Shadows** - Depth and elevation effects
- **Disabled states** - Visual indication when disabled

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [File item › Remove](./remove.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features

---

*Generated on February 17, 2026*
