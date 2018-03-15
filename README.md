# rollup-plugin-babel-null-convention

Repro of https://github.com/rollup/rollup-plugin-babel/issues/197

```sh
yarn
yarn build
```

You should see an error similar to what's in `build.log`.

```sh
git checkout rollup-plugin-babel-null-convention-fork
yarn
yarn build
```

You should see a successfully built `index.js` bundle in `lib` folder.
