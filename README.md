# LG TV Ad Block List

A curated hosts list to block advertisements and tracking domains on LG Smart TVs.

## Overview

This blocklist contains domain entries that disable ads, tracking, and unwanted services on LG Smart TVs by redirecting them to `0.0.0.0`.

## Usage

Add the contents of the `list` file to your hosts file or ad-blocking solution (Pi-hole, AdGuard, etc.) to block these domains on your LG TV.


### With Pi-hole:

1. Go to **Adlists** in the Pi-hole dashboard
2. Add a new blocklist:
   - **URL**: Paste the raw URL to the `list` file from this repository
   - Or upload the `list` file directly if you're hosting it locally
3. Click **Add** to import the list
4. The changes will apply to all devices on your network after the list updates


## Contents

The list includes:
- **General domains** - Common ad networks and tracking services
- **US specific section** - US-region specific ad servers and analytics
- **PT specific section** - Portugal-region specific services

## Note

Always backup your hosts file before making changes. Some entries may affect functionality depending on your TV model and usage.
