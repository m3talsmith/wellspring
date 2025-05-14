# Distributed Systems With Go

The source code of the book.

## Development

All writing is done in the `src` directory. Individual files are preferred, but directory structures are acceptable.

### Requirements

- [zola](https://www.getzola.org/)

### Building

```
zola -r src/ build -o release/
```

### Writing

```
zola -r src serve
```