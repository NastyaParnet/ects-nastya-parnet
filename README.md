# ECTS Converter

This project provides a simple JavaScript class to convert numerical scores into the European Credit Transfer and Accumulation System (ECTS) grades.

## Installation

Install ects-converter with npm

```bash
  npm install ects-nastya-parnet
```

## Usage/Examples

```javascript
const ECTS = require("ects-nastya-parnet");

const studentScore = new ECTS(85);
console.log(studentScore.ectsFromScore()); // Output: "B"
```
