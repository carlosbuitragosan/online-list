![Deploy Status](https://github.com/carlosbuitragosan/online-list/actions/workflows/deploy.yml/badge.svg)

# Online List

A lightweight React application for managing simple shopping or task lists. The app demonstrates client-side state management with persistent storage using localStorage, allowing list data to survive page reloads without requiring a backend or database.

## Overview

Add and remove items from a list with instant UI updates. Data is stored locally in the browser using localStorage, allowing the list to persist across sessions while keeping the application completely client-side.

## Stack

React · JavaScript · CSS · Web App Manifest (PWA)

## Deployment

Deployed via a lightweight CI/CD pipeline using GitHub Actions. Each push to main triggers an automated build and deployment workflow that compiles the React production bundle and publishes the build artifact to GitHub Pages.

## Next Steps

- Improve mobile UI and interaction
- Offline-first enhancements
- Optional cloud synchronization