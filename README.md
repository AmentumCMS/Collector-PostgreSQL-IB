# What is this?

[![Release](https://github.com/amentumcms/Collector-PostgreSQL-IB/actions/workflows/collect.yml/badge.svg?branch=main)](https://github.com/amentumcms/Collector-PostgreSQL-IB/actions/workflows/collect.yml)

This is a project that automatically collects artifacts to ease in air-gapped transfer from the internet.

It runs actions on Push or on Mondays at 00:00 and creates a release.

In this case, it collects the source code repositories and the associated container images via skopeo for:

- dso.mil IronBank PostgreSQL Hardened container images
