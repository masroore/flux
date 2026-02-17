# Kanban › Column › Cards

> **Category:** kanban
> **Component Name:** `flux:kanban.column.cards`

## Overview

Kanban board for organizing cards in columns.

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:kanban.column.cards
/>
```

### With Livewire

```blade
<flux:kanban.column.cards
    wire:model="property"
/>
```

## Accessibility

- Component follows standard HTML accessibility practices
- Keyboard navigation supported where applicable

## Styling

### Default Styling

The component uses Tailwind CSS classes for styling. Key styling features:


### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [Kanban › Index](./index.md)
- [Kanban › Column › Index](./column-index.md)
- [Kanban › Column › Header](./column-header.md)
- [Kanban › Column › Footer](./column-footer.md)
- [Kanban › Card](./card.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features

---

*Generated on February 17, 2026*
