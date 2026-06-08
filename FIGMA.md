# Figma Connection

Design file: [Design System V2](https://www.figma.com/design/ZllxQplWi5QJcNeUHeY8T3/Design-System-V2?node-id=37-931&t=56OsHoEjij8V1mt0-1)

Figma team: [all projects](https://www.figma.com/files/team/816302178841550835/all-projects)

GitHub repository: [olenakorobets-byte/petproject](https://github.com/olenakorobets-byte/petproject)

## Connected Components

| Figma component | Figma node | Code component | Source |
| --- | --- | --- | --- |
| Button | `37:931` | `Button` | [`apps/v4/registry/new-york-v4/ui/button.tsx`](apps/v4/registry/new-york-v4/ui/button.tsx) |
| Alert | `26:160` | `Alert` | [`apps/v4/registry/new-york-v4/ui/alert.tsx`](apps/v4/registry/new-york-v4/ui/alert.tsx) |

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

## Code Connect Status

The repository-side Figma link is recorded here. The official Figma Code Connect mapping could not be saved from the current Figma account because Figma returned:

```text
You need a Developer seat in an Organization or Enterprise plan to access Code Connect.
```
