# Sell Today vs Master Lease + Option Calculator

## Overview
A financial calculator web application that compares selling a property today on the MLS versus entering into a Master Lease + Option (MLO) arrangement. The calculator helps users analyze different financial scenarios including mortgage calculations, present value analysis, and various cost factors.

## Project Architecture
- **Type**: Static HTML application with embedded CSS and JavaScript
- **Main File**: `index.html` - Complete single-page application
- **Language**: HTML5, CSS3, JavaScript (vanilla)
- **Deployment**: Static web application served via Python HTTP server

## Features
- Interactive calculator with real-time updates
- Two calculation modes:
  - Sell Today (MLS): Traditional property sale with commissions and fees
  - Master Lease + Option: Lease-to-own arrangement with monthly payments
- Advanced features:
  - Present value calculations with customizable discount rates
  - Mortgage amortization vs manual payoff calculations
  - FSBO (For Sale By Owner) mode
  - Collapsible sections for optional inputs
  - Mobile-responsive design

## Technical Setup
- **Frontend Server**: Python HTTP server on port 5000
- **Host Configuration**: Bound to 0.0.0.0 for Replit compatibility
- **Deployment Target**: Autoscale (suitable for static content)

## Recent Changes
- **2025-09-22**: Initial project import from GitHub
  - Renamed main file from 'MLO' to 'index.html'
  - Set up Python HTTP server workflow
  - Configured deployment settings for production
  - Verified application functionality

## User Preferences
- Single-file architecture maintained from original import
- No additional dependencies introduced
- Clean, professional interface preserved

## Current State
- ✅ Application running successfully
- ✅ Web server configured and operational
- ✅ Deployment settings configured
- ✅ All calculator features functional