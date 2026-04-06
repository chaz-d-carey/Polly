# Polly

Polly is a .NET resilience library for handling transient faults in distributed systems.
It provides reusable policies such as Retry, Circuit Breaker, Timeout, Bulkhead, Fallback, and PolicyWrap.

## Install

```powershell
Install-Package Polly
```

## Usage

Define policies at startup, reuse them across services, and execute external calls through them.
Use async policy variants for async code.
