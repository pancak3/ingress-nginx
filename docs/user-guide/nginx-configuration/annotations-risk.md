# Annotations Scope and Risk

|Group   |Annotation        | Risk | Scope |
|--------|------------------|------|-------|
| Aliases | server-alias | High | ingress |
| Allowlist | allowlist-source-range | Medium | location |
| BackendProtocol | backend-protocol | Low | location |
| BasicDigestAuth | auth-realm | Medium | location |
| BasicDigestAuth | auth-secret | Medium | location |
| BasicDigestAuth | auth-secret-type | Low | location |
| BasicDigestAuth | auth-type | Low | location |
| Canary | canary | Low | ingress |
| Canary | canary-by-cookie | Medium | ingress |
| Canary | canary-by-header | Medium | ingress |
| Canary | canary-by-header-pattern | Medium | ingress |
| Canary | canary-by-header-value | Medium | ingress |
| Canary | canary-weight | Low | ingress |
| Canary | canary-weight-total | Low | ingress |
| CertificateAuth | auth-tls-error-page | High | location |
| CertificateAuth | auth-tls-match-cn | High | location |
| CertificateAuth | auth-tls-pass-certificate-to-upstream | Low | location |
| CertificateAuth | auth-tls-secret | Medium | location |
| CertificateAuth | auth-tls-verify-client | Medium | location |
| CertificateAuth | auth-tls-verify-depth | Low | location |
| ClientBodyBufferSize | client-body-buffer-size | Low | location |
| ConfigurationSnippet | configuration-snippet | Critical | location |
| Connection | connection-proxy-header | Low | location |
| CorsConfig | cors-allow-credentials | Low | ingress |
| CorsConfig | cors-allow-headers | Medium | ingress |
| CorsConfig | cors-allow-methods | Medium | ingress |
| CorsConfig | cors-allow-origin | Medium | ingress |
| CorsConfig | cors-expose-headers | Medium | ingress |
| CorsConfig | cors-max-age | Low | ingress |
| CorsConfig | enable-cors | Low | ingress |
| CustomHTTPErrors | custom-http-errors | Low | location |
| CustomHeaders | custom-headers | Medium | location |
| DefaultBackend | default-backend | Low | location |
| Denylist | denylist-source-range | Medium | location |
| DisableProxyInterceptErrors | disable-proxy-intercept-errors | Low | location |
| EnableGlobalAuth | enable-global-auth | Low | location |
| ExternalAuth | auth-always-set-cookie | Low | location |
| ExternalAuth | auth-cache-duration | Medium | location |
| ExternalAuth | auth-cache-key | Medium | location |
| ExternalAuth | auth-keepalive | Low | location |
| ExternalAuth | auth-keepalive-requests | Low | location |
| ExternalAuth | auth-keepalive-share-vars | Low | location |
| ExternalAuth | auth-keepalive-timeout | Low | location |
| ExternalAuth | auth-method | Low | location |
| ExternalAuth | auth-proxy-set-headers | Medium | location |
| ExternalAuth | auth-request-redirect | Medium | location |
| ExternalAuth | auth-response-headers | Medium | location |
| ExternalAuth | auth-signin | High | location |
| ExternalAuth | auth-signin-redirect-param | Medium | location |
| ExternalAuth | auth-snippet | Critical | location |
| ExternalAuth | auth-url | High | location |
| FastCGI | fastcgi-index | Medium | location |
| FastCGI | fastcgi-params-configmap | Medium | location |
| HTTP2PushPreload | http2-push-preload | Low | location |
| LoadBalancing | load-balance | Low | location |
| Logs | enable-access-log | Low | location |
| Logs | enable-rewrite-log | Low | location |
| Mirror | mirror-host | High | ingress |
| Mirror | mirror-request-body | Low | ingress |
| Mirror | mirror-target | High | ingress |
| ModSecurity | enable-modsecurity | Low | ingress |
| ModSecurity | enable-owasp-core-rules | Low | ingress |
| ModSecurity | modsecurity-snippet | Critical | ingress |
| ModSecurity | modsecurity-transaction-id | High | ingress |
| Opentelemetry | enable-opentelemetry | Low | location |
| Opentelemetry | opentelemetry-operation-name | Medium | location |
| Opentelemetry | opentelemetry-trust-incoming-span | Low | location |
| Proxy | proxy-body-size | Medium | location |
| Proxy | proxy-buffer-size | Low | location |
| Proxy | proxy-buffering | Low | location |
| Proxy | proxy-buffers-number | Low | location |
| Proxy | proxy-busy-buffers-size | Low | location |
| Proxy | proxy-connect-timeout | Low | location |
| Proxy | proxy-cookie-domain | Medium | location |
| Proxy | proxy-cookie-path | Medium | location |
| Proxy | proxy-http-version | Low | location |
| Proxy | proxy-max-temp-file-size | Low | location |
| Proxy | proxy-next-upstream | Medium | location |
| Proxy | proxy-next-upstream-timeout | Low | location |
| Proxy | proxy-next-upstream-tries | Low | location |
| Proxy | proxy-read-timeout | Low | location |
| Proxy | proxy-redirect-from | Medium | location |
| Proxy | proxy-redirect-to | Medium | location |
| Proxy | proxy-request-buffering | Low | location |
| Proxy | proxy-send-timeout | Low | location |
| ProxySSL | proxy-ssl-ciphers | Medium | ingress |
| ProxySSL | proxy-ssl-name | High | ingress |
| ProxySSL | proxy-ssl-protocols | Low | ingress |
| ProxySSL | proxy-ssl-secret | Medium | ingress |
| ProxySSL | proxy-ssl-server-name | Low | ingress |
| ProxySSL | proxy-ssl-verify | Low | ingress |
| ProxySSL | proxy-ssl-verify-depth | Low | ingress |
| RateLimit | limit-allowlist | Low | location |
| RateLimit | limit-burst-multiplier | Low | location |
| RateLimit | limit-connections | Low | location |
| RateLimit | limit-rate | Low | location |
| RateLimit | limit-rate-after | Low | location |
| RateLimit | limit-rpm | Low | location |
| RateLimit | limit-rps | Low | location |
| Redirect | from-to-www-redirect | Low | location |
| Redirect | permanent-redirect | Medium | location |
| Redirect | permanent-redirect-code | Low | location |
| Redirect | relative-redirects | Low | location |
| Redirect | temporal-redirect | Medium | location |
| Redirect | temporal-redirect-code | Low | location |
| Rewrite | app-root | Medium | location |
| Rewrite | force-ssl-redirect | Medium | location |
| Rewrite | preserve-trailing-slash | Medium | location |
| Rewrite | rewrite-target | Medium | ingress |
| Rewrite | ssl-redirect | Low | location |
| Rewrite | use-regex | Low | location |
| SSLCipher | ssl-ciphers | Low | ingress |
| SSLCipher | ssl-prefer-server-ciphers | Low | ingress |
| SSLPassthrough | ssl-passthrough | Low | ingress |
| Satisfy | satisfy | Low | location |
| ServerSnippet | server-snippet | Critical | ingress |
| ServiceUpstream | service-upstream | Low | ingress |
| SessionAffinity | affinity | Low | ingress |
| SessionAffinity | affinity-canary-behavior | Low | ingress |
| SessionAffinity | affinity-mode | Medium | ingress |
| SessionAffinity | session-cookie-change-on-failure | Low | ingress |
| SessionAffinity | session-cookie-conditional-samesite-none | Low | ingress |
| SessionAffinity | session-cookie-domain | Medium | ingress |
| SessionAffinity | session-cookie-expires | Medium | ingress |
| SessionAffinity | session-cookie-max-age | Medium | ingress |
| SessionAffinity | session-cookie-name | Medium | ingress |
| SessionAffinity | session-cookie-path | Medium | ingress |
| SessionAffinity | session-cookie-samesite | Low | ingress |
| SessionAffinity | session-cookie-secure | Low | ingress |
| StreamSnippet | stream-snippet | Critical | ingress |
| UpstreamHashBy | upstream-hash-by | High | location |
| UpstreamHashBy | upstream-hash-by-subset | Low | location |
| UpstreamHashBy | upstream-hash-by-subset-size | Low | location |
| UpstreamVhost | upstream-vhost | Low | location |
| UsePortInRedirects | use-port-in-redirects | Low | location |
| XForwardedPrefix | x-forwarded-prefix | Medium | location |

