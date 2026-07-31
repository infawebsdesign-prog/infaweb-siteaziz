# Deployment requirement

Upload the files with this exact structure at the site root:

```
/index.html
/about.html
/contact.html
/privacy.html
/assets/image-0c6de3fb8846.jpg
/assets/image-1f7e16f4d157.jpg
/assets/image-7da5d96534c7.jpg
/assets/image-bceeaf7d6d9e.jpg
```

The HTML now uses root-relative `/assets/...` paths, so images continue to work when pages are served through clean URLs such as `/about`, `/about/`, `/contact`, or `/contact/`.

Do not upload only the HTML files. The complete `assets` folder must be deployed.
