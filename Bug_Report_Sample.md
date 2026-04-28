# Devmatics Studio - Professional Bug Report
**Project:** Devmatics E-Store App  
**Reported By:** SQA Department  
**Date:** April 28, 2026

---

## 1. Bug Overview
| Attribute | Details |
| :--- | :--- |
| **Bug ID** | BUG-2026-001 |
| **Title** | Checkout button unresponsive on iOS devices |
| **Severity** | Critical (S1) |
| **Priority** | High (P1) |
| **Environment** | iPhone 13, iOS 17.4, Safari Browser |
| **Status** | New / Open |

---

## 2. Description
The "Proceed to Checkout" button does not trigger any action when clicked from a mobile browser (Safari) on iOS devices. Users are unable to complete their purchases.

## 3. Steps to Reproduce
1. Open the application on an iPhone Safari browser.
2. Add any item to the cart.
3. Navigate to the Cart page.
4. Click on the **"Proceed to Checkout"** button.

## 4. Expected Result
The user should be redirected to the Shipping & Payment information page.

## 5. Actual Result
Nothing happens. No error message is displayed, and the button remains unresponsive.

## 6. Evidence & Attachments
* **Screenshot:** `[attached_image_checkout_error.png]`
* **Console Log:** `ReferenceError: checkoutHandler is not defined at HTMLButtonElement.onclick`

---
### **Note:**
*This bug has been flagged for immediate fix as it impacts the revenue-generating path of the application.*
