# webhint

webhint helps you improve your site's accessibility, speed, cross-browser compatibility, and more by checking your code for best practices and common errors.

- accessibility
- development
- compatibility
- performance
- pwa
- pitfalls
- security

## install

```bash
npm install hint --save-dev
```

```json
{
    ...
    "scripts": {
        "webhint": "hint http://localhost:5173"
    }
}
```

```bash
npm run webhint
```


## npm run webhint

```
~/workspace/pwa-portal$ npm run webhint

> pwa-portal@0.0.1 webhint
> hint http://localhost:5173

Using the built-in configuration.
Visit https://webhint.io/docs/user-guide/ to learn how to create your own configuration.
✖ Finishing...
You can view the HTML report in "/home/rock/workspace/pwa-portal/hint-report/http-localhost-5173.html"
compat-api/html   2 warnings
http-cache        2 warnings
http-compression  2 hints
meta-viewport     2 errors
sri               2 errors
content-type      33 warnings
× Found a total of 4 errors, 37 warnings, 2 hints and 0 informations

```

## references

| Item                                | Link(s)             |
| ----------------------------------- | ------------------- |
| Use webhint to improve your website | https://webhint.io/ |

