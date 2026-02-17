# Pillbox › Search

> **Category:** pillbox
> **Component Name:** `flux:pillbox.search`

## Overview

Multi-select component displaying selected items as pills.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `placeholder` | `mixed` | `null` | Placeholder text when no value is selected |
| `clearable` | `boolean` | `true` | Whether the component shows a clear button |
| `closable` | `mixed` | `null` | Configuration for closable |
| `icon` | `mixed` | `null` | Configuration for icon |

## Supported Attributes

- `wire:model`

## Usage

### Basic Example

```blade
<flux:pillbox.search
    placeholder="Enter value"
/>
```

### Advanced Example

```blade
<flux:pillbox.search
    placeholder="value"
    clearable="value"
    closable="value"
    icon="value"
>
    Advanced content
</flux:pillbox.search>
```

### With Livewire

```blade
<flux:pillbox.search
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

- [Pillbox › Index](./index.md)
- [Pillbox › Options](./options.md)
- [Pillbox › Variants › Combobox](./variants-combobox.md)
- [Pillbox › Variants › Default](./variants-default.md)
- [Pillbox › Trigger](./trigger.md)

## Technical Notes

- Supports Livewire `wire:model` binding
- Uses Alpine.js for reactive behavior
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
