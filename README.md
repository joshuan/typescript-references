## Example of building packages with and without references

1. Install deps:

`pnpm i`

2. Build with references:

`pnpm run build --filter with-refs`

3. Clean

`pnpm run clean -r`

4. Build without references:

`pnpm run build --filter without-refs` (Broken)
