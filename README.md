# Nextui-Vite

A vite typescript app to test [nextui](https://nextui.org/) for production

## Getting started
clone the app

```bash
git clone https://github.com/PatrickNiyogitare28/nextui-vite.git
```

```bash
cd nextui-vite
```

```bash
yarn install
```

### Running the dev server
```bash
yarn dev
```

### Building for production
```bash
yarn build
```

## The current state
currently [nextui ALPHA](https://nextui.org/)  building for ts vite is failing.

### Logs
The [vercel](https://vercel.com/) building error logs

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/PatrickNiyogitare28/nextui-vite)


```js
Cloning github.com/PatrickNiyogitare28/nextui-vite (Branch: master, Commit: 1264667)
Cloning completed: 350.909ms
Analyzing source code...
Installing build runtime...
Build runtime installed: 2.578s
Looking up build cache...
Build Cache not found
Detected package.json
Installing dependencies...
yarn install v1.22.17
[1/4] Resolving packages...
[2/4] Fetching packages...
[3/4] Linking dependencies...
warning " > jest-scss-transform@1.0.1" has incorrect peer dependency "babel-jest@^24.8.0".
[4/4] Building fresh packages...
Done in 16.68s.
Running "yarn run build"
yarn run v1.22.17
$ tsc && vite build
node_modules/@nextui-org/react/esm/theme/common.d.ts(235,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(235,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(240,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(245,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(245,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(250,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(255,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(260,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(260,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(263,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(263,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(268,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(271,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(271,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(276,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(281,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(281,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(286,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(291,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(296,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(296,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(301,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(304,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(309,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(309,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(312,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(317,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(322,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(322,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(327,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(327,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(332,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(338,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(338,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(341,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(346,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(346,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(351,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(351,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(356,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(361,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(361,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(366,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(371,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(376,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(376,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(381,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(386,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(386,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(391,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(396,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(396,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(401,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(401,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(410,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(410,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(415,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(418,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(418,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(423,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(426,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(431,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(431,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(436,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(436,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(441,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(441,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(446,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(446,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(451,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(456,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(456,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(461,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(472,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(472,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(477,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(477,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(482,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(487,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(487,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(492,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(497,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(502,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(502,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(505,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(510,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(513,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(513,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(518,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(523,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(528,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(528,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(533,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(538,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(538,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(543,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(548,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(548,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(551,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(551,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(556,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(556,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(559,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(559,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(562,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(565,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(565,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(570,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(570,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(573,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(573,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(578,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(578,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(581,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(961,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(961,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(964,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(964,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(968,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(968,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(971,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(975,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(975,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(978,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(978,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(982,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(985,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(985,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(989,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(989,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(992,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(992,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(996,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(996,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(999,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1002,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1002,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1006,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1006,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1009,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1009,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1012,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1012,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1016,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1016,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1019,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1019,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1023,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1023,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1026,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1026,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1030,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1030,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1033,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1033,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1037,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1037,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1040,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1040,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1044,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1044,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1047,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1047,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1051,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1054,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1054,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1057,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1057,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1061,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1061,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1064,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1067,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1067,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1071,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1071,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1074,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1074,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1078,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1078,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1081,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1085,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1085,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1088,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1088,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1092,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1092,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1095,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1095,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1099,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1103,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1103,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1106,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1106,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1110,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1110,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1113,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1113,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1117,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1120,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1120,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1124,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1124,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1127,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1127,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1131,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1131,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1134,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1134,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1138,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1138,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1141,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1141,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1145,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1145,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1148,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1152,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1152,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1155,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1155,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1159,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1159,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1162,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1162,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1166,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1169,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1169,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1173,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1173,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1176,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1176,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1180,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1180,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1183,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1183,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1187,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1187,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1190,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1190,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1194,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1194,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1200,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1203,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1203,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1207,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1207,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1210,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1210,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1213,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1217,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1217,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1220,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1220,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1223,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1223,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1227,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1227,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1230,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1234,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1234,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1237,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1237,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1241,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1241,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1244,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1244,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1248,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1251,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1251,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1255,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1255,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1258,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1258,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1262,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1262,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1265,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1269,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1269,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1272,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1272,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1276,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1276,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1281,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1281,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1286,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1289,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1289,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1293,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1293,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1296,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1296,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1300,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1300,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1303,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1307,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1307,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1310,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1310,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1314,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1314,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1317,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1317,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1321,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1324,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1324,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1328,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1328,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1331,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1331,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1334,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1338,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1338,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1341,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1341,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1344,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1344,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1348,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1348,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1351,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1351,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1355,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1355,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1358,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1358,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1362,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1362,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1365,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1365,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1369,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1372,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1372,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1376,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1376,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1379,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1379,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1383,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1383,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1386,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1390,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1390,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1393,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1393,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1396,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1396,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1400,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1400,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1403,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1403,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1406,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1406,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1409,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1409,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1412,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1416,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1416,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1419,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1419,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1422,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1422,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1426,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1426,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1429,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1432,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1432,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1436,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1436,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1441,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1441,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1446,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/common.d.ts(1446,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6421,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6424,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6424,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6428,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6428,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6431,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6431,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6435,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6435,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6438,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6442,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6442,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6445,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6445,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6449,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6449,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6452,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6452,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6456,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6459,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6459,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6462,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6462,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6466,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6466,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6469,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6472,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6472,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6476,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6476,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6479,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6479,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6483,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6483,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6486,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6490,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6490,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6493,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6493,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6497,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6497,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6500,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6504,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6504,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6507,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6507,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6511,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6511,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6514,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6514,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6517,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6521,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6521,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6524,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6524,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6527,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6527,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6531,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6531,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6534,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6538,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6538,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6541,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6541,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6545,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6545,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6548,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6548,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6552,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6555,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6555,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6559,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6559,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6563,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6563,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6566,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6566,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6570,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6570,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6573,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6573,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6577,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6577,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6580,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6580,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6584,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6584,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6587,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6587,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6591,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6591,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6594,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6594,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6598,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6601,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6601,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6605,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6605,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6608,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6608,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6612,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6612,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6615,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6615,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6619,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6619,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6622,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6622,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6626,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6626,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6629,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6629,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6633,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6633,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6636,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6636,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6640,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6640,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6643,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6643,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6647,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6647,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6650,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6650,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6654,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6654,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6660,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6660,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6663,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6663,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6667,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6670,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6670,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6673,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6673,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6677,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6677,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6680,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6680,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6683,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6683,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6687,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6687,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6690,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6690,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6694,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6694,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6697,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6697,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6701,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6701,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6704,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6704,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6708,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6708,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6711,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6711,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6715,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6715,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6718,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6718,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6722,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6722,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6725,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6725,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6729,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6732,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6732,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6736,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6736,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6741,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6741,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6746,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6746,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6749,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6749,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6753,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6753,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6756,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6756,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6760,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6760,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6763,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6763,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6767,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6767,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6770,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6770,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6774,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6774,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6777,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6777,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6781,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6781,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6784,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6784,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6788,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6788,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6791,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6791,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6794,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6794,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6798,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6801,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6801,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6804,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6804,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6808,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6808,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6811,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6811,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6815,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6815,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6818,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6818,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6822,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6822,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6825,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6825,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6829,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6829,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6832,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6832,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6836,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6836,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6839,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6839,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6843,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6843,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6846,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6846,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6850,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6850,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6853,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6853,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6856,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6856,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6860,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6863,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6863,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6866,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6866,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6869,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6869,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6872,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6872,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6876,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6876,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6879,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6879,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6882,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6882,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6886,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6886,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6889,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6889,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6892,26): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6892,27): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6896,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6896,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6901,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6901,23): error TS2304: Cannot find name '$$PropertyValue'.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6906,22): error TS1170: A computed property name in a type literal must refer to an expression whose type is a literal type or a 'unique symbol' type.
node_modules/@nextui-org/react/esm/theme/stitches.config.d.ts(6906,23): error TS2304: Cannot find name '$$PropertyValue'.
error Command failed with exit code 2.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
Error: Command "yarn run build" exited with 2
```

## Maintainer
patrickniyogitare28@gmail.com