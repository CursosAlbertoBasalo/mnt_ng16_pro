# Add Layout

## 1.- Generate module core with layout components

```bash
ng g m core
ng g c core/layout/header --flat --export --inline-style --skip-tests --change-detection=OnPush
ng g c core/layout/footer --flat --export --inline-style --skip-tests --change-detection=OnPush
```

## 2.- Generate an small module shared with atoms components

```bash
ng g m shared/atoms
ng g c shared/atoms/link --flat --export --inline-style --skip-tests --change-detection=OnPush --type=atom
```
