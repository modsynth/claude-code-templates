# Create API Endpoint

Create a new API endpoint using Modsynth modules.

1. Use api-gateway for routing
2. Use auth-module for authentication
3. Use db-module for data access
4. Use logging-module for logging

Example:
```go
package main

import (
    "github.com/modsynth/api-gateway"
    "github.com/modsynth/auth-module/middleware"
)

func main() {
    gw := gateway.New()
    authMw := middleware.NewAuthMiddleware(jwtManager)
    
    gw.Router().GET("/api/users", authMw.Authenticate(handleUsers))
    gw.Run(":8080")
}
```
