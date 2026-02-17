# Accordion › Heading

> **Category:** accordion
> **Component Name:** `flux:accordion.heading`

## Overview

Collapsible content sections that can be expanded or collapsed.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `disabled` | `mixed` | `null` | Whether the component is disabled |
| `variant` | `mixed` | `null` | Visual style variant of the component |

## Inherited Props (via @aware)

These props are inherited from parent components:

- `disabled`
- `variant`

## Default Slot

This component accepts a default slot for its main content.

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:accordion.heading
>
    Content here
</flux:accordion.heading>
```

### With Livewire

```blade
<flux:accordion.heading
    wire:model="property"
/>
```

## Accessibility

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
- [Accordion › Icon](./icon.md)
- [Accordion › Item](./item.md)

## Technical Notes

- Standard Blade component implementation

---

*Generated on February 17, 2026*
