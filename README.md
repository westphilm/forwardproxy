# ForwardProxy
## Python Port Forwarding Proxy

This is a port-forwarding proxy. It connects to another server:port and returns the received data. Useful for server-side redirects to local services or resources, e.g. cam streams. So you can hide services from public access, but enable controlled access through the proxy.

The embedded authentication module protects the proxy itself against unauthorized access. This is only an example implementation, which works with 2 plain text URL-Parameters. You can us it, how it is (you shouldn't!), you can replace it with your own authentication module or you can disable the authentication.

Jann Westphal 02/2020
