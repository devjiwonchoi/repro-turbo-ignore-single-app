Steps to reproduce

Run the following commands:

```sh
pnpm i
pnpm turbo build
npx turbo-ignore
```

Confirm that the `packages` value is missing

```sh
pnpm turbo build --dry=json
```