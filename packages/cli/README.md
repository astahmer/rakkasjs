This is the development CLI package for [Rakkas.JS](https://rakkasjs.org).

```
Usage: rakkas [options] [command]

Options:
  -V, --version   output the version number
  -h, --help      display help for command

Commands:
  dev [options]   Start a development server
      -p, --port <port>  port number (default: "3000")
      -H, --host <host>  host (default: "localhost")
  build           Build for production
  print-config    Print configuration
  help [command]  display help for command
```

The `build` command also supports the following option:

```
-d, --deployment-target <target>  Deployment target (choices: "node", "static", "vercel", "netlify", "cloudflare-workers", default: "node")
```

See the [website](https://rakkasjs.org) for details.