# ✅ Content Delivery Network (CDN) - Quick Notes

![CDN Diagram](images/cdn-diagram.png)

## Definition
A Content Delivery Network (CDN) is a network of geographically distributed servers that deliver web content (images, videos, CSS, JavaScript, etc.) to users based on their location, ensuring faster access and lower latency.

---

## How It Works

- **Caching:** Static content is cached on CDN edge servers located in multiple geographic locations.
- **Request Routing:** User requests are routed to the nearest CDN server, reducing latency.
- **Content Delivery:** The CDN serves the cached content or retrieves it from the origin server if not cached.

---

## Key Benefits

- **Faster Content Delivery:** Reduces load times by serving content from the nearest server.
- **Scalability:** Handles traffic spikes efficiently.
- **Reliability:** Provides redundancy and failover in case of server outages.
- **Security:** Protects against DDoS attacks and malicious traffic.

---

## Examples of CDN Providers

- **Azure CDN** - Integrates with Azure services for global content distribution.
- **Cloudflare CDN** - Provides security and performance optimization.
- **Amazon CloudFront** - Delivers content using AWS infrastructure.
- **Akamai CDN** - Offers advanced caching and edge computing features.

---

## Example Use Case

A news website with users across multiple countries uses Azure CDN to cache and deliver images and videos. Users in India access content from a nearby Indian server, while users in the US get content from a US-based server, ensuring faster load times and a seamless experience.
