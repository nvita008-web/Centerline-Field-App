# Centerline Field App

A mobile-friendly progressive web app (PWA) built for on-site equine nutrition consultations.

## Features

- Client and horse profile management
- Body condition score (BCS) tracking with visual graph
- Visit notes with auto-saving quick notes
- Diet, supplement, and medication logs
- Lab value tracking (insulin, Vitamin E, glucose, ACTH)
- Photo storage per client (up to 4)
- PIN-based authentication
- Full offline capability via browser local storage
- Export/import data backup as JSON

## Technical Notes

Built with vanilla HTML, CSS, and JavaScript — no frameworks or dependencies. Kept intentionally lightweight and self-contained for reliable offline use on iPad in low-connectivity environments (barns, farms).

Data persists in browser local storage. The export/import feature allows data transfer between devices and serves as a manual backup system.

## Context

Built to support [Centerline Equine Nutrition](https://centerlineequinenutrition.com), an independent equine nutrition consulting practice founded by Nicole A. Vita, PhD — a computational chemist and Certified Equine Nutrition Advisor specializing in evidence-based feeding strategies for horses.

## Usage

Open `index.html` in any modern browser. For the best mobile experience on iPad, open in Safari and use **Add to Home Screen** to install as a PWA.
