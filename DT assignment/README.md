# Reflection Decision Tree Dashboard

## Overview
The **Reflection Decision Tree Dashboard** is an interactive, web-based tool designed to guide users through a guided self-reflection session at the end of their workday. 

Rather than functioning as a standard survey, it acts as a dynamic decision tree. As the user answers questions about their day, the dashboard actively analyzes their responses to determine their "mental state" and professional orientation across three key psychological axes. At the end of the session, it provides a tailored, coach-like evaluation of their current professional stance.

## Key Features
- **Dynamic Scrolling Interface**: Built to mimic a conversational flow, new questions and reflections smoothly fade in and scroll into view based on user input.
- **Embedded Decision Logic**: The system routes the user down different conversational paths depending on how they answer.
- **Psychological Signal Tracking**: The application quietly tracks user choices across three behavioral axes:
  1. **Locus (Agency)**: `Internal` (focusing on what you can control) vs. `External` (focusing on systemic constraints).
  2. **Orientation**: `Contribution` (giving freely) vs. `Entitlement` (protecting energy and seeking fair return).
  3. **Radius (Awareness)**: `Others` (team-focused) vs. `Self` (individual outcome-focused).
- **Professional Coach Evaluation**: At the end of the decision tree, the dashboard aggregates the dominant signals to generate a personalized behavioral persona (e.g., *The Empowered Catalyst*, *The Guarded Contributor*) alongside a breakdown of the user's mental state and standout capabilities.
- **Zero Dependencies**: The entire project is built using vanilla HTML, CSS, and JavaScript. It runs entirely in the browser with no need for a backend or local server (all data is embedded directly into the code).

## Technology Stack
- **HTML5**: For the semantic structure of the dashboard container.
- **CSS3**: For the modern, sleek dark-mode aesthetic. Features include CSS variables for easy theming, custom animations (`@keyframes fadeIn`), and flexbox layouts.
- **Vanilla JavaScript**: For parsing the TSV (Tab-Separated Values) logic, handling the DOM manipulation, tracking the `signals` state, and calculating the final coach evaluation.

## How to Run
Simply double-click the `index.html` file to open it in your default web browser. Since the decision tree logic is securely embedded within the JavaScript file, you do not need to run a local web server to bypass CORS issues. It works instantly right out of the box.
