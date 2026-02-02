# JavaScript Security Code Injection and eval()

## Objective
This assignment demonstrates two JavaScript security vulnerabilities and their fixes:

1. JavaScript code injection (DOM-based XSS)
2. Dynamic runtime code evaluation using `eval()`

Each vulnerability is shown with a vulnerable example and a secure implementation.

---

## How to Run
Open the HTML files directly in a web browser.

- `xss/vulnerable-xss.html` and `xss/fixed-xss.html`  
  Demonstrate DOM-based JavaScript injection and its mitigation.

- `eval/vulnerable-eval.html` and `eval/fixed-eval.html`  
  Demonstrate unsafe dynamic code evaluation using `eval()` and a secure alternative.

Malicious inputs can be tested in the vulnerable files and verified as blocked in the fixed versions.

---

## Summary
This assignment shows how insecure JavaScript practices lead to client-side attacks and how safe DOM handling and removal of `eval()` prevent exploitation.
