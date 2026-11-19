### Findings Summary

| No. | Finding | Evidence | Observation |
|---|---|---|---|
| 1 | HTTP service detected | Nmap scan | TCP port 80 is open. |
| 2 | HTTPS service unavailable | Nmap scan | TCP port 443 is closed. |
| 3 | Web application accessible | Nmap and curl | Server returned HTTP 200 OK. |
| 4 | Wildcard CORS configuration | HTTP headers | `Access-Control-Allow-Origin: *` was observed. Requires further investigation. |
| 5 | Browser security headers present | HTTP headers | `X-Content-Type-Options: nosniff` and `X-Frame-Options: SAMEORIGIN` were identified. |

**Overall Observation:**

The active footprinting process successfully identified an accessible OWASP Juice Shop web application running on the local Kali machine. The scan identified an open HTTP port, a closed HTTPS port, and several HTTP response headers. The wildcard CORS configuration was recorded as an observation requiring further assessment. No exploitable vulnerability has been confirmed through these scans alone.
