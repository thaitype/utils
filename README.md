# mild-ts
Opinionated TypeScript Utility Libraries

## Required

- TypeScript 5.0 and above


- [retry-helper](https://github.com/actions/checkout/blob/ac593985615ec2ede58e132d2e21d2b1cbd6127c/src/retry-helper.ts)
- ConsoleLogger

```ts
// https://pawelgrzybek.com/make-the-typescript-interface-partially-optional-required/
export type PartialRequired<T, K extends keyof T> = Omit<T, K> & Required<Pick<T, K>>;
```