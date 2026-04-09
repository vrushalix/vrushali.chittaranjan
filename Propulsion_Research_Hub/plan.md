# Implementation Plan: Propulsion Research Hub

## Overview
Build a premium, high-fidelity research paper explorer focused on space propulsion. The app will serve as a centralized dashboard for searching and tracking publications across major aerospace journals and open-source repositories.

## 1. Design Concept
- **Aesthetic**: "Deep Space Nebula" – Dark theme with subtle glowing gradients, glassmorphism containers, and high-contrast typography.
- **Typography**: `Inter` and `Fira Code` (for DOI/Metadata) from Google Fonts.
- **Key Features**:
    - Centralized Search Bar with propulsion-specific filters (e.g., Electric Propulsion, Chemical, Nuclear).
    - Source-specific search routing (redirects to journal-specific search results).
    - Integrated arXiv browser for open-source papers.
    - "Pulse" feed for recent aerospace breakthroughs.

## 2. Technical Stack
- **Structure**: Semantic HTML5.
- **Style**: Custom CSS with CSS Variables for theme management.
- **Logic**: Vanilla JavaScript for search construction and API fetching (arXiv).

## 3. Data Sources & Integration
| Source | Type | Integration Method |
| :--- | :--- | :--- |
| **arXiv** | Open Source | API Fetch (XML to JSON) |
| **AIAA / IEEE / ScienceDirect** | Publisher | Direct Search URL Construction |
| **NASA NTRS** | Open Source | Search Routing |

## 4. UI Components
1. **Header**: Animated nebula background with logo.
2. **Search Console**: Floating glassmorphic input with multi-select source filters.
3. **Journal Grid**: Quick-access cards to major aerospace databases.
4. **Live Feed**: A sidebar showing recent papers from open sources.
