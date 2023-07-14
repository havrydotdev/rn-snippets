# The essential collection of React ans Next Snippets

![Example](https://github.com/gavrylenkoIvan/rn-snippets/blob/main/snippet.gif)

## Full Expansions

### uc:

```typescript
"use client"
```

### fc :

```tsx
    export const ComponentName = (): React.JSX.Element => {
        return <div>Content</div>;
    };
```

### fcp: 

```tsx
    export const ComponentName = (Props: PropsType): React.JSX.Element => {
        return <div {...props}>Content</div>;
    };
```

### lt:

```tsx
export default function LayoutName({
    children
}: {
    children: React.ReactNode;
}): React.JSX.Element {
    return <div>Content</div>;
}
```

### fc:

```tsx
export const ComponentName = (): React.JSX.Element => {
    return <div>Content</div>;
};
```
