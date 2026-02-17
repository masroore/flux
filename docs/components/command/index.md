# Command › Index

> **Category:** command
> **Component Name:** `flux:command.index`

## Overview

Command palette for quick actions and search.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `placeholder` | `mixed` | `null` | Placeholder text when no value is selected |

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:command.index
    placeholder="Enter value"
/>
```

### With Livewire

```blade
<flux:command.index
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

- [Command › Items](./items.md)
- [Command › Input](./input.md)
- [Command › Item](./item.md)
- [Command › Empty](./empty.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
