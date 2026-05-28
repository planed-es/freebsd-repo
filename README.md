# How to

Create the following file at `/usr/local/etc/pkg/repos/planedes.conf`

```
planedes: {
  url:      "https://planed-es.github.io/freebsd-repo",
  enabled:  yes,
  priority: 10
}
```

And run `pkg update`
