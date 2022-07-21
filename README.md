# React Financial Charts

> **Note:** this repo is a fork of [react-stockcharts](https://github.com/rrag/react-stockcharts), renamed, converted to typescript and bug fixes applied due to the original project being unmaintained.

> **Note:** v1 is a fully breaking change with large parts, if not all, rewritten. Do not expect the same API! although the same features should exist.

![ci](https://github.com/react-financial/react-financial-charts/workflows/ci/badge.svg)
[![codecov](https://codecov.io/gh/reactivemarkets/react-financial-charts/branch/master/graph/badge.svg)](https://codecov.io/gh/reactivemarkets/react-financial-charts)
[![npm version](https://img.shields.io/npm/v/react-financial-charts.svg?style=flat)](https://www.npmjs.com/package/react-financial-charts)

Charts dedicated to finance.

The aim with this project is create financial charts that work out of the box.

## Features

- integrates multiple chart types
- technical indicators and overlays
- drawing objects

### Chart types

- Scatter
- Area
- Line
- Candlestick
- OHLC
- HeikenAshi
- Renko
- Kagi
- Point & Figure

### Indicators

- EMA, SMA, WMA, TMA
- Bollinger band
- SAR
- MACD
- RSI
- ATR
- Stochastic (fast, slow, full)
- ForceIndex
- ElderRay
- Elder Impulse

### Interactive Indicators

- Trendline
- Fibonacci Retracements
- Gann Fan
- Channel
- Linear regression channel

---

## Installation

```sh
npm install react-financial-charts
```

## Contributing

Refer to [CONTRIBUTING.md](./CONTRIBUTING.md)

This project is a mono-repo that uses [Lerna](https://lerna.js.org/) to manage dependencies between packages.

To get started run:

```bash
git clone https://github.com/Powerful2100/react-financial-charts.git
cd react-financial-charts
npm ci
npm run build
```

To start up a development server run:

```bash
npm start
```

## Roadmap

- [x] Convert to typescript
- [x] Bump dependencies to latest
- [x] Remove React 16 warnings
- [x] Add CI
- [x] Fix passive scrolling issues
- [x] Implement PRs from react-stockcharts
- [x] Add all typings
- [x] Move examples to storybook
- [x] Add all series' to storybook
- [x] Split project into multiple packages
- [x] Fix issues with empty datasets
- [x] Correct all class props
- [x] Migrate to new React Context API
- [x] Remove all UNSAFE methods
- [ ] Add documentation to storybook
- [ ] Add full test suite
