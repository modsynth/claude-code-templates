# Setup Frontend

Setup a new React frontend with Modsynth modules.

Install required modules:
```bash
npm install @modsynth/ui-components
npm install @modsynth/api-client
npm install @modsynth/auth-client
npm install @modsynth/state-management
npm install @modsynth/routing
```

Setup structure:
```tsx
import { Button } from '@modsynth/ui-components';
import { ApiClient } from '@modsynth/api-client';
import { BrowserRouter, Routes, Route } from '@modsynth/routing';

function App() {
  return (
    <BrowserRouter>
      <Routes>
        <Route path="/" element={<Home />} />
      </Routes>
    </BrowserRouter>
  );
}
```
