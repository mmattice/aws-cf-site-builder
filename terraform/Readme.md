# build-terraform 

This script takes one argument - the site name you're building.

```
./build-terraform www.example.com
```

What that does is builds a ${website}-cf-website.tf file from the cf-website.tf.in template.

Unfortunately, it seems (https://github.com/hashicorp/terraform/issues/6139) that terraform doesn't yet support multiple ACLs per bucket.  **AND** the log-delivery-write canned ACL doesn't apply the correct permissions as of terraform 0.9.4.
