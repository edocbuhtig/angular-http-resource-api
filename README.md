# httpResource API 
- git clone
- npm install 
 - For any NPM Errors on Mac OS:
```

sudo chown -R 501:20 "/Users/macusername/.npm"

```
- The New Resource API is still dependent on the former httpClient provider:
```
import { provideHttpClient } from '@angular/common/http';
```
