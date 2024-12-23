## API Report File for "@backstage-community/plugin-code-coverage-backend"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
import { AuthService } from '@backstage/backend-plugin-api';
import { BackendFeature } from '@backstage/backend-plugin-api';
import { CatalogApi } from '@backstage/catalog-client';
import { Config } from '@backstage/config';
import { DatabaseService } from '@backstage/backend-plugin-api';
import { DiscoveryService } from '@backstage/backend-plugin-api';
import express from 'express';
import { HttpAuthService } from '@backstage/backend-plugin-api';
import { LoggerService } from '@backstage/backend-plugin-api';
import { UrlReaderService } from '@backstage/backend-plugin-api';

// @public
const codeCoveragePlugin: BackendFeature;
export default codeCoveragePlugin;

// @public @deprecated (undocumented)
export function createRouter(options: RouterOptions): Promise<express.Router>;

// @public @deprecated (undocumented)
export interface RouterOptions {
  // (undocumented)
  auth?: AuthService;
  // (undocumented)
  catalogApi?: CatalogApi;
  // (undocumented)
  config: Config;
  // (undocumented)
  database: DatabaseService;
  // (undocumented)
  discovery: DiscoveryService;
  // (undocumented)
  httpAuth?: HttpAuthService;
  // (undocumented)
  logger: LoggerService;
  // (undocumented)
  urlReader: UrlReaderService;
}
```
