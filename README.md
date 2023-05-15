# Styles `@material` on Storybook of Next app

## Steps I followed

1. `npx create-next-app@latest my-next-app`
2. `cd my-next-app`
3. `npx sb init`
4. `npm i @material/button @material/top-app-bar`
5. Import style in [`stories/Button.tsx`](stories/Button.tsx)
6. `npm run storybook` and show Button story

## Result

Styles are not applied.

Ref: [https://github.com/nrwl/nx/issues/16962](https://github.com/nrwl/nx/issues/16962)
