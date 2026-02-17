# Kanban › Column › Header

> **Category:** kanban
> **Component Name:** `flux:kanban.column.header`

## Overview

Kanban board for organizing cards in columns.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `heading` | `mixed` | `null` | Configuration for heading |
| `subheading` | `mixed` | `null` | Configuration for subheading |
| `count` | `mixed` | `null` | Configuration for count |
| `badge` | `mixed` | `null` | Configuration for badge |

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:kanban.column.header
/>
```

### Advanced Example

```blade
<flux:kanban.column.header
    heading="value"
    subheading="value"
    count="value"
    badge="value"
>
    Advanced content
</flux:kanban.column.header>
```

### With Livewire

```blade
<flux:kanban.column.header
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

- [Kanban › Index](./index.md)
- [Kanban › Column › Index](./column-index.md)
- [Kanban › Column › Cards](./column-cards.md)
- [Kanban › Column › Footer](./column-footer.md)
- [Kanban › Card](./card.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features

---

*Generated on February 17, 2026*
