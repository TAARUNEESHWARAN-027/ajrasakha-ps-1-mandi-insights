# Mandi-Insights
### Unified Market Data Aggregator & Analytics Engine

## Overview
Mandi-Insights is a market intelligence module built for the Ajrasakha platform. It aims to consolidate fragmented agricultural market price data from multiple official sources into a unified, normalized, and searchable system.

## Problem Statement
Indian mandi price data is scattered across eNAM, Agmarknet, and numerous state-level portals, leaving farmers without a single reliable source for complete market visibility or historical insights.

## Proposed Solution
- Aggregate mandi price data from verified public sources
- Normalize crop names, units, and date formats
- Provide basic analytics and trend visualization
- Design for low-bandwidth, mobile-first access

## MVP Scope (Phase 1)
- Data sources: Agmarknet + one selected state portal
- Coverage: Limited mandis and crops for demonstration
- Features:
  - Daily data ingestion
  - Data normalization
  - Time-series price charts
  - Simple market comparison view

## Planned Enhancements (Phase 2+)
- Expand to multiple state portals
- Coverage tracking for APMCs
- Advanced analytics and alerts
- Price forecasting models
- Data export (CSV / Excel)

## Tech Stack
- Frontend: React.js
- Backend: Node.js, Express.js
- Database: MongoDB
- Data Processing: Python (optional)

## Ajrasakha Integration
Designed to integrate seamlessly with Ajrasakha’s MERN-based architecture and follow platform standards.

## Current Status
Project initialization and planning stage.

## License
MIT (to be added)
