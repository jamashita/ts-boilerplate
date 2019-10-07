# ts-boilerplate

this repository is for typescript beginners  
you can start typescript soon with this repository :))

## requirement

this repository is assumed to work in such environment as below.

 ```
> node -v
v12.10.0

> npm -v               
6.10.3

> yarn -v
1.19.0
```

## run

there are some reserved `npm-scripts`.  
here are they.

```
yarn start
```
start js program. the entrypoint is `dist/index.js`

```
yarn compile
```
translate `src/*.ts` files into `dist/*.js` files
 
```
yarn dev
```
start `ts` program without translating. the entrypoint is `src/index.ts`

```
yarn watch
``` 
start `ts` program without translating. one the codes are changed, it will automatically restart the program.

```
yarn clean
```
remove `dist/*.js` files

```
yarn build
```
automatically remove `dist/*.js` and translate `src/*.ts`