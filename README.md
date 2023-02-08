## [vite-dashboard][2]

`vite-dashboard` is a basic gin-gonic webserver for the KOGAS project.

## Disclaimer
> This tool is limited to security research only, and the user assumes all legal and related responsibilities arising from its use! The author assumes no legal responsibility!

## install
```bash
cd vite-dashboard

npm install
npm run dev
```

## config
Config the package json file 
```json
{
  "name": "vite-dashboard",
  "private": true,
  "version": "1.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview"
  },
  "devDependencies": {
    "vite": "^4.1.0"
  }
}
```

## Run
```bash
npm run dev

open http://127.0.0.1:5174/
```



[2]: https://pkg.go.dev/github.com/teocci/vite-dashboard
[3]: https://github.com/teocci/vite-dashboard/releases/tag/v1.0.0
