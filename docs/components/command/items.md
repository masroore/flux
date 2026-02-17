# Command › Items

> **Category:** command
> **Component Name:** `flux:command.items`

## Overview

Command palette for quick actions and search.

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:command.items
/>
```

### With Livewire

```blade
<flux:command.items
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

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [Command › Index](./index.md)
- [Command › Input](./input.md)
- [Command › Item](./item.md)
- [Command › Empty](./empty.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
