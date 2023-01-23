IMUL Timestamps shall begin with the absolute time in the following format called an ASCII Timestamp.

```IMUL
@2021-01-03;01:02
```

After the absolute time has been specified, scripts may refer to the time delta in `@minutes` or `@minutes:seconds` format as follows:

```IMUL
@10
@20:30
```

The `@10` means it's 10 minutes after `@2021-01-03;01:02`, which is `@2021-01-03;01:12`. The second time delta is 20 minutes and 30 seconds past `@2021-01-03;01:12`, which is `@2021-01-03;01:32:30`.