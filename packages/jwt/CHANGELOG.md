# @cfworker/jwt

## 7.0.4

### Patch Changes

- 4379518: Update dependencies

## 7.0.3

### Patch Changes

- 04a079e: Update dependencies

## 7.0.2

### Patch Changes

- b7b602d: Use tshy: Hybrid (CommonJS/ESM) TypeScript node package builder, to produce builds

## 7.0.1

### Patch Changes

- a72875c: Restore type:module

## 7.0.0

### Major Changes

- c6e2d7b: Remove package.type for better compatibility with esm and cjs

## 6.0.1

### Patch Changes

- e4f2167: Update dependencies

## 6.0.0

### Major Changes

- f7c148d: Add support for CommonJS by adding exports field to all packages. Thanks @dannyball710 !!

## 5.2.1

### Patch Changes

- 89458c0: isolatedModules, isolatedDeclarations

## 5.2.0

### Minor Changes

- 8b0e94b: Set package type to module

### Patch Changes

- 93a12c7: Don't include tsconfig.json in package #237 #261

## 5.1.1

### Patch Changes

- 4d04224: Fix export of InvalidJwtReasonCode

## 5.1.0

### Minor Changes

- f140592: Add reason code and decoded JWT header and payload to invalid JWT parse result.

## 5.0.0

### Major Changes

- 805c92f: Update all dependencies, use latest workers-types, deprecate cfworker dev in favor of wrangler
- 206bec0: Refactor parseJwt to use a single options parameter. Add an option to customize the clock skew allowance when validating iat, nbf, and exp claims. Change the default clock skew from 30 to 60 seconds. Include jwt header in parse result.

## 4.0.6

### Patch Changes

- 3209b6a: Support an array of allowed issuers when calling parseJwt

## 4.0.5

### Patch Changes

- e1d4a23: Add jku to JwtHeader typedef

## 4.0.4

### Patch Changes

- fc4c040: Update dependencies
- Updated dependencies [fc4c040]
  - @cfworker/worker-types@1.12.3

## 4.0.3

### Patch Changes

- 1748ed6: Update dependencies
- Updated dependencies [1748ed6]
  - @cfworker/worker-types@1.12.2

## 4.0.2

### Patch Changes

- 84f9f99: Remove jwks promise cache

## 4.0.1

### Patch Changes

- fabe900: Reuse jwks imports

## 4.0.0

### Major Changes

- 37df6b6: Use OIDC discovery document to locate public keyset

## 3.0.0

### Major Changes

- 073acc7: Validate iat and nbf. Permit 30 seconds of clock skew. Enable supplying custom public key resolver to parseJwt.

## 2.0.0

### Major Changes

- bc29475: Add support for RS384 and RS512

### Patch Changes

- 03090fb: Migrate from @cfworker/base64url and base64-arraybuffer to rfc4648

## 1.12.2

### Patch Changes

- 8a6a815: Upgrade to node 16.14.0
- Updated dependencies [8a6a815]
  - @cfworker/base64url@1.12.2

## 1.12.1

### Patch Changes

- d2390db: Update dependencies
- Updated dependencies [d2390db]
  - @cfworker/base64url@1.12.1
  - @cfworker/worker-types@1.12.1

## 1.12.0

### Minor Changes

- 5ed7223: Downgrade @cloudflare/workers-types to 2.2.2

### Patch Changes

- Updated dependencies [5ed7223]
  - @cfworker/base64url@1.12.0
  - @cfworker/worker-types@1.12.0

## 1.11.0

### Minor Changes

- 122dcd9: Update @cloudflare/workers-types to 3.2.x and TypeScript to 4.5.x

### Patch Changes

- Updated dependencies [122dcd9]
  - @cfworker/base64url@1.11.0
  - @cfworker/worker-types@1.11.0

## 1.10.2

### Patch Changes

- 390ce91: Update Typescript to 4.5.2
- Updated dependencies [390ce91]
  - @cfworker/base64url@1.10.2
  - @cfworker/worker-types@1.10.2
