# No Internet Connectivity Issue

## Problem
User cannot access internet websites.

## Troubleshooting Steps

1. Check IP address
ipconfig (Windows) / ifconfig (Linux)

2. Check gateway connectivity
ping 192.168.1.1

3. Check external connectivity
ping google.com

4. Check DNS resolution
nslookup google.com

## Result
Identified DNS issue and resolved by changing DNS server.
