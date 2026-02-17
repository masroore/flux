# Pillbox › Options

> **Category:** pillbox
> **Component Name:** `flux:pillbox.options`

## Overview

Multi-select component displaying selected items as pills.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `searchPlaceholder` | `mixed` | `null` | Configuration for searchPlaceholder |
| `searchable` | `mixed` | `null` | Whether the component is searchable |
| `search` | `mixed` | `null` | Configuration for search |
| `empty` | `mixed` | `null` | Configuration for empty |
| `indicator` | `mixed` | `null` | Configuration for indicator |

## Inherited Props (via @aware)

These props are inherited from parent components:

- `searchable`

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:pillbox.options
/>
```

### Advanced Example

```blade
<flux:pillbox.options
    searchPlaceholder="value"
    searchable="value"
    search="value"
    empty="value"
>
    Advanced content
</flux:pillbox.options>
```

### With Livewire

```blade
<flux:pillbox.options
    wire:model="property"
/>
```

## Accessibility

- Component follows standard HTML accessibility practices
- Keyboard navigation supported where applicable

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

- [Pillbox › Index](./index.md)
- [Pillbox › Variants › Combobox](./variants-combobox.md)
- [Pillbox › Variants › Default](./variants-default.md)
- [Pillbox › Trigger](./trigger.md)
- [Pillbox › Option](./option.md)

## Technical Notes

- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
