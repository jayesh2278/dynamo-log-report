An Apache-style access log is provided at /app/access.log. Read it and produce a JSON summary of the traffic.

Write your report to /app/report.json as a single JSON object with exactly these three keys:
- "total_requests": integer — the number of log entries (non-empty lines).
- "unique_ips": integer — the number of distinct client IP addresses (the first field on each line).
- "top_path": string — the request path that appears most often.

Success criteria:
1. /app/report.json exists and contains a single valid JSON object.
2. "total_requests" equals the total number of log entries.
3. "unique_ips" equals the number of distinct client IP addresses.
4. "top_path" is the most frequently requested path.
