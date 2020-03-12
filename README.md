# CSRF Demo: Bad Site

This site is a malicious website designed to abuse [CSRF Demo: Good Site](https://github.com/ryl/cybr406-goodsite)

If the Good Site does not have CSRF protection enabled, this site can initiate a transfer of funds. **Bad!**

If the Good Site has CSRF protection enabled, this site will get an error, and no funds will be transferred. **Good!**

View at [http://localhost:8081](http://localhost:8081).