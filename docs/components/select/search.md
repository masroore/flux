# Select › Search

> **Category:** select
> **Component Name:** `flux:select.search`

## Overview

Dropdown select component with search and filtering.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `clearable` | `boolean` | `true` | Whether the component shows a clear button |
| `closable` | `mixed` | `null` | Configuration for closable |
| `icon` | `mixed` | `null` | Configuration for icon |

## Supported Attributes

- `wire:model`

## Usage

### Basic Example

```blade
<flux:select.search
/>
```

### Advanced Example

```blade
<flux:select.search
    clearable="value"
    closable="value"
    icon="value"
>
    Advanced content
</flux:select.search>
```

### With Livewire

```blade
<flux:select.search
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

- [Select › Options](./options.md)
- [Select › Variants › Custom](./variants-custom.md)
- [Select › Variants › Combobox](./variants-combobox.md)
- [Select › Variants › Listbox](./variants-listbox.md)
- [Select › Indicator › Index](./indicator-index.md)

## Technical Notes

- Supports Livewire `wire:model` binding
- Uses Alpine.js for reactive behavior
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
