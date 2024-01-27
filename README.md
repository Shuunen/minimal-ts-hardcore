# Minimalist TS Project for Hardcore Eslint

Here is a minimalist TS project trying to check the minimum time required by eslint-config-hardcore to parse a single & simple ts file.

Using `hyperfine --runs 3 --warmup 1 'npx eslint main.ts'` we get the following results:

It takes 6.5 seconds to check this single file with eslint-config-hardcore.

What's happening here ?

Is it expected ?
