# parcel-tsconfig-extends-repro

## Steps to reproduce issue
1. In packages/app, run `yarn build`
   1. App doesn't build
2. Run `yarn add -D parcel@2.8.3`
3. Run `yarn build`
   1. App builds
