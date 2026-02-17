# File upload › Index

> **Category:** file-upload
> **Component Name:** `flux:file-upload.index`

## Overview

File upload interface with drag-and-drop support.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `name` | `mixed` | `$attributes->whereStartsWith('wire:model')->first()` | Form field name attribute |

## Default Slot

This component accepts a default slot for its main content.

## Supported Attributes

- `wire:model`

## Usage

### Basic Example

```blade
<flux:file-upload.index
    name="field_name"
/>
```

### With Livewire

```blade
<flux:file-upload.index
    wire:model="property"
/>
```

## Accessibility

- Component follows standard HTML accessibility practices
- Keyboard navigation supported where applicable

## Styling

### Default Styling

The component uses Tailwind CSS classes for styling. Key styling features:


### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [File upload › Dropzone › Index](./dropzone-index.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Supports Livewire `wire:model` binding
- Contains `wire:ignore` regions for JavaScript library integration
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
