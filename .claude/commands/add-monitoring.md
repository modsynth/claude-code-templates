# Add Monitoring

Add Prometheus monitoring to your application.

1. Install monitoring-module:
```bash
go get github.com/modsynth/monitoring-module
```

2. Add metrics endpoint:
```go
import "github.com/modsynth/monitoring-module"

http.Handle("/metrics", monitoring.Handler())
```

3. Record metrics:
```go
monitoring.RecordMetrics("GET", "/api/users", "200", duration)
```

4. Access metrics at http://localhost:8080/metrics
