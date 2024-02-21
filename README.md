Test Repository for possible Hugo issues
========================================

# Problems with `static` files and mounts

## 0.122.0

```
$ hugo-0.122.0
Start building sites …
hugo v0.122.0-b9a03bd59d5f71a529acb3e33f995e0ef332b3aa+extended darwin/arm64 BuildDate=2024-01-26T15:54:24Z

WARN  Dir layouts/partials/shortcodes/metadata not found

                   | EN  
-------------------+-----
  Pages            | 20  
  Paginator pages  |  0  
  Non-page files   |  0  
  Static files     |  2  
  Processed images |  0  
  Aliases          |  7  
  Sitemaps         |  1  
  Cleaned          |  0  

Total in 57 ms

$ ls public/images/
header.svg	screenshot.png

```

### 0.123.1

```
$ hugo
Start building sites …
hugo v0.123.1-3f8434a62fc91a50f4e5bd43a4435d2d301844ff+extended darwin/arm64 BuildDate=2024-02-21T08:17:45Z VendorInfo=brew

WARN  Dir layouts/partials/shortcodes/metadata not found

                   | EN  
-------------------+-----
  Pages            | 21  
  Paginator pages  |  0  
  Non-page files   |  0  
  Static files     |  1  
  Processed images |  0  
  Aliases          |  7  
  Cleaned          |  0  

Total in 54 ms
$ ls public/images/
screenshot.png
```
