---
title: "Generate Array of Random Numbers"
language: "javascript"
twitter: "rolandjlevy"
---
function arrayOfRandomNumbers (length) {
  return Array.from(new Array(length), () => Math.round(Math.random() * 10));
}
