# Command › Input

> **Category:** command
> **Component Name:** `flux:command.input`

## Overview

Command palette for quick actions and search.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `clearable` | `mixed` | `null` | Whether the component shows a clear button |
| `closable` | `mixed` | `null` | Configuration for closable |
| `icon` | `string` | `'magnifying-glass'` | Configuration for icon |

## Usage

### Basic Example

```blade
<flux:command.input
/>
```

### Advanced Example

```blade
<flux:command.input
    clearable="value"
    closable="value"
    icon="value"
>
    Advanced content
</flux:command.input>
```

### With Livewire

```blade
<flux:command.input
    wire:model="property"
/>
```

## Accessibility

- ARIA labels are properly set for screen readers
- Comprehensive ARIA attributes for accessibility
- Keyboard navigation support with proper focus management

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
- [Command › Items](./items.md)
- [Command › Item](./item.md)
- [Command › Empty](./empty.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Uses Alpine.js for reactive behavior
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
