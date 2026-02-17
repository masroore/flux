# Accordion › Icon

> **Category:** accordion
> **Component Name:** `flux:accordion.icon`

## Overview

Collapsible content sections that can be expanded or collapsed.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `pointing` | `string` | `'down'` | Configuration for pointing |
| `disabled` | `mixed` | `null` | Whether the component is disabled |

## Inherited Props (via @aware)

These props are inherited from parent components:

- `disabled`

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:accordion.icon
>
    Content here
</flux:accordion.icon>
```

### With Livewire

```blade
<flux:accordion.icon
    wire:model="property"
/>
```

## Accessibility

- Comprehensive ARIA attributes for accessibility
- Disabled states are properly communicated to assistive technologies

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
- [Accordion › Content](./content.md)
- [Accordion › Heading](./heading.md)
- [Accordion › Item](./item.md)

## Technical Notes

- Standard Blade component implementation

---

*Generated on February 17, 2026*
