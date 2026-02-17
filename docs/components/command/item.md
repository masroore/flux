# Command › Item

> **Category:** command
> **Component Name:** `flux:command.item`

## Overview

Command palette for quick actions and search.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `iconVariant` | `string` | `'outline'` | Configuration for iconVariant |
| `icon` | `mixed` | `null` | Configuration for icon |
| `kbd` | `mixed` | `null` | Configuration for kbd |

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:command.item
/>
```

### Advanced Example

```blade
<flux:command.item
    iconVariant="value"
    icon="value"
    kbd="value"
>
    Advanced content
</flux:command.item>
```

### With Livewire

```blade
<flux:command.item
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

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [Command › Index](./index.md)
- [Command › Items](./items.md)
- [Command › Input](./input.md)
- [Command › Empty](./empty.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
