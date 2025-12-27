<p align="center">
  <a href="https://github.com/clovalink/clovalink">
    <img src="./logo.svg" width="480" alt="ClovaLink Logo" />
  </a>
</p>

# ClovaLink

ClovaLink is a modern, Rust-powered file platform focused on security, performance, and full data ownership.  
It’s designed for organizations that want enterprise features — without enterprise lock-in.

---

## Core Capabilities

- **S3-compatible storage** (AWS, Wasabi, MinIO, B2, etc.)
- **S3 replication** for redundancy & disaster recovery
- **Built-in antivirus scanning (ClamAV)**
- **Zero-copy file deduplication**
- **Versioning, soft delete, and recovery**
- **Secure sharing with expiring links**
- **Multi-tenant architecture**
- **Role-based access control and audit logs**

---

## Reliability & Architecture

ClovaLink is built to be resilient in real production environments:

- **Circuit breaker patterns** to protect downstream services  
- **Retry & backoff queues** for storage operations  
- **Cascading replication rules** (primary → secondary → cold storage)  
- **Health checks & service watchdogs**
- **Transaction-safe metadata updates**
- **Cache-aware read/write flows**

Every upload is validated, scanned, stored, and replicated through controlled workflows — with observability at each step.

---

## Security First

- Real-time malware scanning (ClamAV)  
- Optional auto-quarantine / auto-suspend for repeated malicious activity  
- Signed URLs and scoped tokens  
- Immutable audit history  
- Tenant-isolated storage and permissions  

Security is built into the engine — not added later.

---

## Why ClovaLink?

Other “enterprise” storage systems are expensive, restrictive, and closed.  
ClovaLink focuses on:

- self-hosting and privacy  
- predictable costs  
- performance at scale  
- developer extensibility  

You own the data, infrastructure, and roadmap.

---

## License

MIT — use it, fork it, build on it.

---

🔗 https://github.com/clovalink

