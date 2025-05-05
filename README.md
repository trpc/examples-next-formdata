# Next.js + tRPC + `FormData`

This example showcases how to use tRPC with `FormData`.

It relies on the latest '@next' version of trpc, using `zod-form-data` (see `./src/utils/schemas.ts`) and `splitLink` in `./src/utils/trpc.ts` to handle `FormData` requests.

## Setup

```bash
npx create-next-app --example https://github.com/trpc/trpc --example-path examples/next-formdata trpc-formdata
cd trpc-formdata
npm i
npm run dev
```
