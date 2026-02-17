# Accordion › Content

> **Category:** accordion
> **Component Name:** `flux:accordion.content`

## Overview

Collapsible content sections that can be expanded or collapsed.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `transition` | `boolean` | `false` | Enable transition animations |
| `expanded` | `boolean` | `false` | Whether the component is initially expanded |

## Inherited Props (via @aware)

These props are inherited from parent components:

- `transition`
- `expanded`

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:accordion.content
>
    Content here
</flux:accordion.content>
```

### With Livewire

```blade
<flux:accordion.content
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

- [Accordion › Index](./index.md)
- [Accordion › Heading](./heading.md)
- [Accordion › Icon](./icon.md)
- [Accordion › Item](./item.md)

## Technical Notes

- Standard Blade component implementation

---

*Generated on February 17, 2026*
