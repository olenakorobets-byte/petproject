# Figma Connection

Design file: [Design System V2](https://www.figma.com/design/ZllxQplWi5QJcNeUHeY8T3/Design-System-V2?node-id=37-931&t=56OsHoEjij8V1mt0-1)

Figma team: [all projects](https://www.figma.com/files/team/816302178841550835/all-projects)

GitHub repository: [olenakorobets-byte/petproject](https://github.com/olenakorobets-byte/petproject)

## Connected Components

| Figma component | Figma node | Code component | Source |
| --- | --- | --- | --- |
| Button | `37:931` | `Button` | [`apps/v4/registry/new-york-v4/ui/button.tsx`](apps/v4/registry/new-york-v4/ui/button.tsx) |
| Alert | `26:160` | `Alert` | [`apps/v4/registry/new-york-v4/ui/alert.tsx`](apps/v4/registry/new-york-v4/ui/alert.tsx) |
| Accordion | `22:1330` | `Accordion` | [`apps/v4/registry/new-york-v4/ui/accordion.tsx`](apps/v4/registry/new-york-v4/ui/accordion.tsx) |
| Accordion / AccordionItem | `22:516` | `AccordionItem` | [`apps/v4/registry/new-york-v4/ui/accordion.tsx`](apps/v4/registry/new-york-v4/ui/accordion.tsx) |
| Alert Dialog | `83:122` | `AlertDialogContent` | [`apps/v4/registry/new-york-v4/ui/alert-dialog.tsx`](apps/v4/registry/new-york-v4/ui/alert-dialog.tsx) |
| Aspect Ratio | `28:1540` | `AspectRatio` | [`apps/v4/registry/new-york-v4/ui/aspect-ratio.tsx`](apps/v4/registry/new-york-v4/ui/aspect-ratio.tsx) |

## Button Mapping

The Figma `Button` component set contains these variants:

- Variants: `Default`, `Secondary`, `Destructive`, `Outline`, `Ghost`, `Link`
- States: `Default`, `Focus`, `Hover`, `Disabled`, `Loading`, `Pressed`
- Sizes: `default`, `icon`, `sm`, `lg`

The matching React component supports:

- `variant`: `default`, `secondary`, `destructive`, `outline`, `ghost`, `link`
- `size`: `default`, `sm`, `lg`, `icon`
- native button props such as `disabled`

Official Figma Code Connect source URL:

```text
https://github.com/olenakorobets-byte/petproject/blob/main/apps/v4/registry/new-york-v4/ui/button.tsx
```

## Alert Mapping

The Figma `Alert` component set contains these variants:

- Variants: `Default`, `Destructive`

The matching React component supports:

- `variant`: `default`, `destructive`
- composition with `AlertTitle` and `AlertDescription`

Official Figma Code Connect source URL:

```text
https://github.com/olenakorobets-byte/petproject/blob/main/apps/v4/registry/new-york-v4/ui/alert.tsx
```

## Accordion Mapping

The Figma `Accordion` component maps to the React `Accordion` root component.

The Figma `Accordion / AccordionItem` component set contains these variants:

- Active: `Off`, `On`
- States: `Default`, `Pressed`, `Focus`, `Hover`

The matching React source exports:

- `Accordion`
- `AccordionItem`
- `AccordionTrigger`
- `AccordionContent`

Official Figma Code Connect source URL:

```text
https://github.com/olenakorobets-byte/petproject/blob/main/apps/v4/registry/new-york-v4/ui/accordion.tsx
```

## Alert Dialog Mapping

The Figma `Alert Dialog` component set contains these variants:

- Breakpoints: `md`, `sm`

The matching React source exports the alert dialog primitives, and the visual dialog container maps most closely to `AlertDialogContent`:

- `size`: `default`, `sm`
- composition with `AlertDialogHeader`, `AlertDialogTitle`, `AlertDialogDescription`, `AlertDialogFooter`, `AlertDialogAction`, and `AlertDialogCancel`

Official Figma Code Connect source URL:

```text
https://github.com/olenakorobets-byte/petproject/blob/main/apps/v4/registry/new-york-v4/ui/alert-dialog.tsx
```

## Aspect Ratio Mapping

The Figma `Aspect Ratio` component set contains these ratio variants:

- `1:1`, `5:4`, `4:5`, `4:3`, `3:4`, `3:2`, `2:3`, `16:10`, `10:16`
- `1.618:1`, `1:1.618`, `16:9`, `9:16`, `2:1`, `1:2`, `21:9`, `9:21`

The matching React component supports Radix `AspectRatio` props, including `ratio`.

Official Figma Code Connect source URL:

```text
https://github.com/olenakorobets-byte/petproject/blob/main/apps/v4/registry/new-york-v4/ui/aspect-ratio.tsx
```

## Code Connect Status

The repository-side Figma link is recorded here. The official Figma Code Connect mapping could not be saved from the current Figma account because Figma returned:

```text
You need a Developer seat in an Organization or Enterprise plan to access Code Connect.
```
