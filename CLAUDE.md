# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This repository stores premium and third-party WordPress plugin `.zip` files that must be downloaded from vendor websites (not available via wordpress.org). Each plugin lives in its own directory with a README linking to the official source.

## Structure

- Each plugin has its own directory (e.g., `acf-pro/`, `wpml/`, `wp-graphql-content-blocks/`)
- Each directory contains the plugin `.zip` and a `README.md` with the plugin name and vendor links
- The root `README.md` links to the latest `.zip` in each directory

## When adding or updating a plugin

1. Place the `.zip` in the appropriate directory (create one if it's a new plugin)
2. Add or update the directory's `README.md` with plugin name and official download link
3. Update the root `README.md` to link to the latest `.zip`
4. Remove any old versions of the same plugin from the directory
