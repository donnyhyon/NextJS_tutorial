This is a starter template for [Learn Next.js](https://nextjs.org/learn).

Create a new nextJS app.

```
npx create-next-app <appname>
```


OR

```
npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn/tree/master/basics/learn-starter"
```



Run dev server
```
npm run dev
```

Goto locahost:3000

# Link pages

```
import Link from 'next/link'

Read <Link href="/path for page"> Next page> </Link>
```
Link lazy loads pages.i,e pre-loads only that are linked for faster response.
Pages that are not linked will not be pre-loaded.

# Head

```
import Head from 'next/head'
      <Head>
        <title>Create Next App</title>
        <link rel="icon" href="/favicon.ico" />
      </Head>

<Head>
    <title>First Post</title>
</Head>
```

https://nextjs.org/learn/basics/assets-metadata-css/layout-component