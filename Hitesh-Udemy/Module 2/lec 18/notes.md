# 📘 Node.js vs Browser JS Differences

### some functions are available in node.js and others are avaable in browser js 

## fetch
- `fetch` is **not defined** in Node.js (before v18) but works in the browser.  
  → Because it is a **Browser API**.  
  - In Node.js, we usually use `node-fetch` or built-in fetch (from Node v18+).

## window
- `window` is a **browser global object**.  
- Not available in Node.js (Node uses `global` instead).

## Functions
- `alert` → Browser-only (not in Node.js).  
- `setTimeout`, `setInterval`, `console.log` → ✅ Available in both Browser and Node.js.  
