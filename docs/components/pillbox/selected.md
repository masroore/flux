# Pillbox › Selected

> **Category:** pillbox
> **Component Name:** `flux:pillbox.selected`

## Overview

Multi-select component displaying selected items as pills.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `placeholder` | `mixed` | `null` | Placeholder text when no value is selected |
| `suffix` | `mixed` | `null` | Configuration for suffix |
| `size` | `mixed` | `null` | Size variant of the component |
| `max` | `mixed` | `null` | Configuration for max |
| `input` | `mixed` | `null` | Configuration for input |

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:pillbox.selected
    placeholder="Enter value"
/>
```

### Advanced Example

```blade
<flux:pillbox.selected
    placeholder="value"
    suffix="value"
    size="value"
    max="value"
>
    Advanced content
</flux:pillbox.selected>
```

### With Livewire

```blade
<flux:pillbox.selected
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
- **Hover states** - Interactive feedback on hover

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [Pillbox › Index](./index.md)
- [Pillbox › Options](./options.md)
- [Pillbox › Variants › Combobox](./variants-combobox.md)
- [Pillbox › Variants › Default](./variants-default.md)
- [Pillbox › Trigger](./trigger.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Contains `wire:ignore` regions for JavaScript library integration
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
