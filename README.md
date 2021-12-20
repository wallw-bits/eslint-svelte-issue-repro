# eslint svelte issue reproduction

This is a "minimal" reproduction of an issue with svelte's eslint plugin.

## Reproduce

1. `npm i`
1. `npm run lint`

## Recreate from scratch

1. `npm init svelte@next my-app`
	skeleton
	yes to typescript
	yes to eslint
1. `cd my-app`
1. add `src/test.svelte`
