# Next.js Blank Page Production Bug

This repository demonstrates a common yet elusive bug in Next.js where the application renders a blank page on a production deployment, but works correctly in development.

## Problem

A Next.js application, seemingly correctly configured, displays a blank page when deployed to production environments.  The application renders correctly in development mode.

## Setup

Clone this repository and follow the installation instructions below.

1.  **Clone:** `git clone git@github.com:yourusername/nextjs-blank-page.git`
2.  **Navigate:** `cd nextjs-blank-page`
3.  **Install:** `npm install`
4.  **Run Development:** `npm run dev` (This will work fine)
5.  **Run Build:** `npm run build`
6.  **Run Production:** `npm run start` (This will show the blank page bug)

## Solution

The solution and explanation is provided in the file `index.solution.js`.  It highlights a common cause for blank pages (missing or incorrect configuration).