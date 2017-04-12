# .htaccess RewriteCond for Spam HTTP Referrals (HTTP_REFERER)

## Getting Started

Ready to block some automated spam traffic? Good.

By reviewing referrers in Google Analytics, we've put together a handy .htaccess snippet to block referral traffic from multiple referrers. These referrers are based on traffic to dozens of websites made and/or supervised by FWD:labs.

### Prerequisites

Apache

### Installing

1. Add the snippet of code to your existing .htaccess file anywhere below "RewriteEngine On" or "RewriteBase /" in your site's .htaccess file.

Example:

```
Options +FollowSymLinks
RewriteEngine On
RewriteBase /

# Paste .htaccess below
```

2. Review your site to make sure your .htaccess is working; if you see any errors, revisit the code you just added

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
