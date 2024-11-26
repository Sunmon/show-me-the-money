# server

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v1.1.37. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.


---

libs
사용 라이브러리는 package.json 참고.

- express -> bun 내장 함수 있으나(Bun.serve) express가 레퍼런스가 많아서 사용.

사용하지 않는 라이브러리

- nodemon -> bun 내장 hotreload로 대체
- test -> bun 내장 //https://bun.sh/docs/test/writing