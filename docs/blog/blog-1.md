---
title: Kyverno Golden Image Validator
description: Enforce approved golden container images in Kubernetes with Kyverno policies for supply chain security.
---

# Kyverno Golden Image Validator

Kyverno enables policy-based enforcement of approved "golden" container images in Kubernetes clusters, ensuring only vetted, secure images deploy. This prevents supply chain risks from unapproved or vulnerable images.

## Why Golden Images Matter

Golden images represent pre-scanned, hardened base images that teams maintain for consistency and security. Enforcing them via Kyverno reduces attack surfaces by blocking arbitrary images at admission time.

## To Do