# Accordion › Item

> **Category:** accordion
> **Component Name:** `flux:accordion.item`

## Overview

Collapsible content sections that can be expanded or collapsed.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `transition` | `boolean` | `false` | Enable transition animations |
| `disabled` | `boolean` | `false` | Whether the component is disabled |
| `expanded` | `boolean` | `false` | Whether the component is initially expanded |
| `heading` | `mixed` | `null` | Configuration for heading |

## Inherited Props (via @aware)

These props are inherited from parent components:

- `transition`

## Default Slot

This component accepts a default slot for its main content.

## Supported Attributes

- `wire:model`
- `disabled`

## Usage

### Basic Example

```blade
<flux:accordion.item
>
    Content here
</flux:accordion.item>
```

### Advanced Example

```blade
<flux:accordion.item
    transition="value"
    disabled="value"
    expanded="value"
    heading="value"
>
    Advanced content
</flux:accordion.item>
```

### With Livewire

```blade
<flux:accordion.item
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
- [Accordion › Heading](./heading.md)
- [Accordion › Icon](./icon.md)

## Technical Notes

- Supports Livewire `wire:model` binding
- Uses Alpine.js for reactive behavior
- Implements two-way data binding with Alpine.js
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
