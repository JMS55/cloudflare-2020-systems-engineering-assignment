# CLI
```
cloudflare-2020-systems-engineering-assignment 1.0
JMS55
Tool for making HTTP/1.1 requests and measuring statistics about them.

USAGE:
    cloudflare-2020-systems-engineering-assignment [OPTIONS] --url <url>

FLAGS:
    -h, --help       Prints help information
    -V, --version    Prints version information

OPTIONS:
        --profile <number_of_requests>
        --url <url>
```

# Results
```
cloudflare-2020-systems-engineering-assignment --url https://cloudflare-2020-general-engineering-assignment.jsch.workers.dev/links --profile 10

Number of requests: 10.
Fastest time: 35.239523ms.
Slowest time: 86.307982ms.
Mean time: 49.183448ms.
Median time: 48.97904ms.
Success percentage: 1.
Error codes: [].
Smallest response size: 779 bytes.
Largest response size: 779 bytes.
```

```
cloudflare-2020-systems-engineering-assignment --url http://cloudflare.com --profile 10

Number of requests: 10.
Fastest time: 24.740203ms.
Slowest time: 34.204529ms.
Mean time: 29.169094ms.
Median time: 30.062483ms.
Success percentage: 0.
Error codes: [301, 301, 301, 301, 301, 301, 301, 301, 301, 301].
Smallest response size: 600 bytes.
Largest response size: 600 bytes.```
```

```
cloudflare-2020-systems-engineering-assignment --url http://example.com --profile 10

Number of requests: 10.
Fastest time: 17.890987ms.
Slowest time: 19.96363ms.
Mean time: 18.644593ms.
Median time: 18.662886ms.
Success percentage: 1.
Error codes: [].
Smallest response size: 1609 bytes.
Largest response size: 1632 bytes.
```
