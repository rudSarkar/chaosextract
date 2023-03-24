## Chaos Extract

This tool can extract sudomains from `https://chaos.projectdiscovery.io/` and save into output file.

#### Install

```bash
go install github.com/rudSarkar/chaosextract@latest
```

#### Usage

```bash
chaosextract [options]
```

#### Options

- `-c`: Number of concurrent download threads (default 30)
- `-o`: The name and location of the output file

#### Example

```bash
chaosextract -c 60 -o /tmp/chaos-sub.txt
```
