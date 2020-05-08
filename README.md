# squid-node-utils
Utilities for server-side functions

## Functions
- `pathExists (filePath: string): boolean`
- `requiresPathToExist (filePath: string): void`
- `isDirectory (filePath: string): boolean`
- `requiresPathBeADir (filePath: string): void`
- `isFile (filePath: string): boolean`
- `requiresPathToBeAFile (filePath: string): void`
- `readFile (filePath: string, encoding = 'utf-8'): string`
- `readJson (filePath: string): JsonType`
- `createDirsOfPathIfNotExists (filePath: string): void`
- `writeFile (filePath: string, data: any): void`
- `writeJson (filePath: string, json: JsonType): void`
- `deletePath (filePath: string): void`
- ```
  const walkDirTree = (rootDir: string,
                               opts?: {
                                 fileNameMatcher?: RegExp | ((filePath: string) => boolean);
                                 recursive?: boolean;
                               }): string[]
  ```
