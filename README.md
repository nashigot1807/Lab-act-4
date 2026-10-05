# IT-OOPROG21 | Laboratory Activity 4 | Encapsulation

* **Name:** Igot, Nash Alexander I.
* **Section:** BSIT-2E 
* **Course & Activity:** IT-OOPROG21 - Lab 4 Encapsulation
* **Date:** October 5, 2026



## Overview
This activity refactors the original constructor-based `Vehicle` class to enforce encapsulation rules:
- Encapsulated `brand`, `model`, and `year` as `private`.
- Added public getters for all fields (`getBrand()`, `getModel()`, `getYear()`).
- Enforced constructor validation for `year` (valid range: 1886 to 2026 inclusive; defaults to 2026 if invalid).
- Added `public boolean setYear(int year)` returning `true` for valid updates (1886–2026) and `false` for invalid attempts while preserving the original year state.

