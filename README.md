![Logo](admin/forecastsolar.png)

# ioBroker.forecastSolar

[![NPM version](http://img.shields.io/npm/v/iobroker.forecastsolar.svg)](https://www.npmjs.com/package/iobroker.forecastsolar)
[![Downloads](https://img.shields.io/npm/dm/iobroker.forecastsolar.svg)](https://www.npmjs.com/package/iobroker.forecastsolar)
[![Dependency Status](https://img.shields.io/david/forelleblau/iobroker.forecastsolar.svg)](https://david-dm.org/forelleblau/iobroker.forecastsolar)
[![Known Vulnerabilities](https://snyk.io/test/github/forelleblau/ioBroker.forecastsolar/badge.svg)](https://snyk.io/test/github/forelleblau/ioBroker.forecastsolar)

[![NPM](https://nodei.co/npm/iobroker.forecastsolar.png?downloads=true)](https://nodei.co/npm/iobroker.forecastsolar/)

**Tests:**: [![Travis-CI](http://img.shields.io/travis/forelleblau/ioBroker.forecastsolar/master.svg)](https://travis-ci.org/forelleblau/ioBroker.forecastsolar)

## forecastSolar adapter for ioBroker

1-day solar production estimate for specific location  and a specific plane orientation for an installed module power. Based on a 'public' account of <https://forecast.solar/>

### Getting started

Specify location (lat & long), declination (0 = flat, 90 = vertical), azimuth (0=S, 90=W, -90=E), and installed kWp of your pv-power-plant.

### Data

You get estimatied values for the actual production in watts and the sum of energy produced in watt hours for every hour of the actual and the following day.

## Changelog

### 0.0.1

-   (forelleblau) initial release

## License

MIT License

Copyright (c) 2020 Marcel Adam <marceladam@gmx.ch>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
forelleblauS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
