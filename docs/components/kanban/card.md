# Kanban › Card

> **Category:** kanban
> **Component Name:** `flux:kanban.card`

## Overview

Kanban board for organizing cards in columns.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `heading` | `mixed` | `null` | Configuration for heading |
| `as` | `string` | `'div'` | Configuration for as |
| `header` | `mixed` | `null` | Configuration for header |
| `footer` | `mixed` | `null` | Configuration for footer |

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:kanban.card
/>
```

### Advanced Example

```blade
<flux:kanban.card
    heading="value"
    as="value"
    header="value"
    footer="value"
>
    Advanced content
</flux:kanban.card>
```

### With Livewire

```blade
<flux:kanban.card
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
- **Hover states** - Interactive feedback on hover

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [Kanban › Index](./index.md)
- [Kanban › Column › Index](./column-index.md)
- [Kanban › Column › Header](./column-header.md)
- [Kanban › Column › Cards](./column-cards.md)
- [Kanban › Column › Footer](./column-footer.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
