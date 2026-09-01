# BUG-005 — Checkout allows user to continue without required customer information

## Bug Summary

The checkout process allows the user to continue without entering the required customer information.

## Steps to Reproduce

1. Add a product to the cart.
2. Open the Cart.
3. Click Checkout.
4. Leave the required customer information fields empty.
5. Click Continue.

## Expected Result

The system should display validation messages and prevent the user from continuing.

## Actual Result

The user is allowed to continue without entering the required information.

## Priority

High

## Severity

High

## Status

To Do

## Label

checkout-validation
