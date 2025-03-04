# Notion-to-Bind9 DNS Generator

## Overview

This project automates the process of generating a BIND9 DNS zone file using data from a Notion database table. It extracts domain records from Notion, formats them correctly, and outputs a valid BIND9 zone file.

## Features

- Fetches DNS records from a Notion database.
- Converts the data into a valid BIND9 zone file format.
- Supports multiple record types (A, AAAA, CNAME, MX, TXT, etc.).
- Handles TTL and other optional DNS settings.