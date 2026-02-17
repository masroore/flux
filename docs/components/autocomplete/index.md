# Autocomplete › Index

> **Category:** autocomplete
> **Component Name:** `flux:autocomplete.index`

## Overview

Input field with auto-completion suggestions.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `filter` | `boolean` | `true` | Enable filtering functionality |
| `disabled` | `boolean` | `false` | Whether the component is disabled |

## Default Slot

This component accepts a default slot for its main content.

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:autocomplete.index
/>
```

### With Livewire

```blade
<flux:autocomplete.index
    wire:model="property"
/>
```

## Accessibility

- Disabled states are properly communicated to assistive technologies

## Styling

### Default Styling

The component uses Tailwind CSS classes for styling. Key styling features:


### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [Autocomplete › Items](./items.md)
- [Autocomplete › Item](./item.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
