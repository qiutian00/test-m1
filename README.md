# test-m1

test mac m1 compare with window base intel x64.

## envirnoment

- mac: `mac air m1 2020 16G + 500G ssd;  node v16.5.0(support m1 chip)`
- windows: `HUAWEI MateBook D 14 AMD Ryzen 5 4500U 16G + 350G ssd; node v14.7.0`

### [vite v2.4.2](https://github.com/vitejs/vite) yarn run build

- mac: 29.27s

- windows: 66.46s , 67.26s,  69.12s, 75.3s

### [react v17.0.2](https://github.com/facebook/react) yarn run build

- mac: -

- windows: -

### [vue-next v3.2.0-beta.1](https://github.com/vuejs/vue-next) yarn run build

- mac: -

- windows: 109.14s, 23.77s,  23.67s, 29.62s, 52.66s, 24.65s

### [koa.js v2.13.1](https://github.com/koajs/koa) yarn run build

- mac: -

- windows: cannot build with yarn or npm
