---
name: User Story
about: User story
title: ''
labels: ''
assignees: ''

---

Run pnpm --filter api lint

> api@0.0.1 lint /home/runner/work/gadgetplug/gadgetplug/apps/api
> eslint "{src,apps,libs,test}/**/*.ts" --fix


/home/runner/work/gadgetplug/gadgetplug/apps/api/src/auth/guards/jwt-auth.guard.spec.ts
Warning:   28:5  warning  Promises must be awaited, end with a call to .catch, end with a call to .then with a rejection handler or be explicitly marked as ignored with the `void` operator  @typescript-eslint/no-floating-promises

/home/runner/work/gadgetplug/gadgetplug/apps/api/src/catalog/categories.service.ts
Error:   232:11  error  Unsafe assignment of an error typed value         @typescript-eslint/no-unsafe-assignment
Error:   232:22  error  Unsafe call of a type that could not be resolved  @typescript-eslint/no-unsafe-call
Error:   238:5   error  Unsafe return of a value of type error            @typescript-eslint/no-unsafe-return

/home/runner/work/gadgetplug/gadgetplug/apps/api/src/catalog/products.service.ts
Error:   112:11  error  Unsafe assignment of an error typed value         @typescript-eslint/no-unsafe-assignment
Error:   112:22  error  Unsafe call of a type that could not be resolved  @typescript-eslint/no-unsafe-call
Error:   118:5   error  Unsafe return of a value of type error            @typescript-eslint/no-unsafe-return

/home/runner/work/gadgetplug/gadgetplug/apps/api/src/main.ts
Warning:   76:1  warning  Promises must be awaited, end with a call to .catch, end with a call to .then with a rejection handler or be explicitly marked as ignored with the `void` operator  @typescript-eslint/no-floating-promises

/home/runner/work/gadgetplug/gadgetplug/apps/api/src/vendors/vendors.service.ts
Error:   198:58  error  Unsafe call of a type that could not be resolved  @typescript-eslint/no-unsafe-call
Error:   481:11  error  Unsafe assignment of an error typed value         @typescript-eslint/no-unsafe-assignment
Error:   481:22  error  Unsafe call of a type that could not be resolved  @typescript-eslint/no-unsafe-call
Error:   482:9   error  Unsafe assignment of an error typed value         @typescript-eslint/no-unsafe-assignment
Error:   491:13  error  Unsafe assignment of an error typed value         @typescript-eslint/no-unsafe-assignment

✖ 13 problems (11 errors, 2 warnings)

/home/runner/work/gadgetplug/gadgetplug/apps/api:
 ERR_PNPM_RECURSIVE_RUN_FIRST_FAIL  api@0.0.1 lint: `eslint "{src,apps,libs,test}/**/*.ts" --fix`
Exit status 1
Error: Process completed with exit code 1.
