# Chain: BRIEF-x-forwarded-host-hawk-owin-auth

## Goal
Support X-Forwarded-Host in Hawk OWIN auth — add opt-in proxy host resolution so the OWIN middleware can validate Hawk MACs using the original public hostname forwarded by a reverse proxy, falling back to Request.Host.

## Chain links
*(updated by /chain as links are created)*

## Target
Upstream: `master`
