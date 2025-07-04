# CLASS

This extension provides basic language support for [CLASS](http://ctp.di.fct.unl.pt/CLASS/CLASS-thesisPedroRocha.pdf), a session-typed, higher-order, core language that supports concurrent computation with shared linear state, and which is described in detail in the linked paper.

Authors: Ricardo Antunes

## Release Notes

### 1.12.0

Add `unreachable` process.

### 1.11.0

Add `scan` process.

### 1.10.0

Add `coaffine`, `usage`, `usagel` and `statel` types, handle `cell` with expression and `sshare` process.

### 1.9.0

Add `ccut` and `cpar` processes.

### 1.8.0

Add `fwd!` process.

### 1.7.0

Add `sendty` and `recvty` processes and types.

### 1.6.0

Fix `true` and `false` keywords, added `and`, `or` and `not`.

### 1.5.0

Added the basic primitive types.

### 1.4.1

Support variables in `let` and `let!` processes.

### 1.4.0

Added the `let` and `let!` processes.

### 1.3.0

Added most of affine and shared state features of CLASS (and some other things), along with the new arrow and let syntax.

### 1.2.0

Added the `corec` keyword.

### 1.1.1

Fixed include statement syntax.

### 1.1.0

Added support for unfold and include statements. 

### 1.0.0

Initial release, containing basic support for most features of the language.
