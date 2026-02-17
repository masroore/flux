# File upload › Dropzone › Index

> **Category:** file-upload
> **Component Name:** `flux:file-upload.dropzone.index`

## Overview

File upload interface with drag-and-drop support.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `icon` | `string` | `'cloud-arrow-up'` | Configuration for icon |
| `withProgress` | `boolean` | `false` | Configuration for withProgress |
| `inline` | `boolean` | `false` | Configuration for inline |
| `heading` | `mixed` | `null` | Configuration for heading |
| `text` | `mixed` | `null` | Configuration for text |
| `size` | `mixed` | `null` | Size variant of the component |

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:file-upload.dropzone.index
/>
```

### Advanced Example

```blade
<flux:file-upload.dropzone.index
    icon="value"
    withProgress="value"
    inline="value"
    heading="value"
>
    Advanced content
</flux:file-upload.dropzone.index>
```

### With Livewire

```blade
<flux:file-upload.dropzone.index
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

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [File upload › Index](./index.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features

---

*Generated on February 17, 2026*
