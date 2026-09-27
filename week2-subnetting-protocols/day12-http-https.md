# Day 12: HTTP/HTTPS, Requests & Responses, Status Codes

## 📖 Topic
HTTP is the protocol behind almost everything on the web. Understanding
requests, responses, and status codes is the foundation for web security
work later.

## 🧠 Key Concepts

- **HTTP** (Hypertext Transfer Protocol): a request/response protocol — your
  browser sends a request, the server sends back a response.

- **HTTPS**: HTTP + TLS/SSL encryption. Encrypts the data in transit so it
  can't be read or tampered with by someone intercepting it.
  *Example: logging into a site over HTTP means your password could be
  read in plaintext by anyone on the same network — HTTPS prevents this.*

- **Common HTTP methods**:
  - `GET` — retrieve data (loading a page)
  - `POST` — submit data (submitting a form, logging in)
  - `PUT` — update existing data
  - `DELETE` — remove data

- **Status code categories**:
  - `1xx` — informational
  - `2xx` — success (`200 OK`)
  - `3xx` — redirect (`301 Moved Permanently`, `302 Found`)
  - `4xx` — client error (`403 Forbidden`, `404 Not Found`)
  - `5xx` — server error (`500 Internal Server Error`)

## 💻 Practice Log
- [ ] Opened DevTools → Network tab, inspected requests on 2-3 sites
- [ ] Found a `GET` and a `POST` request
- [ ] Found a `200`, and a `301`/`302` redirect (try `http://github.com`)
- [ ] Looked at request/response headers (`Host`, `User-Agent`, `Content-Type`)

## 📝 My Notes (in my own words)
> Explain HTTP vs HTTPS. List the status codes you actually saw and what
> triggered them. Why does unencrypted HTTP matter for security?

(fill in here)

## ✅ Quiz Results
- Score: __ / __
- Date:
