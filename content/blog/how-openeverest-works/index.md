---
title: "How OpenEverest works"
date: 2025-12-10T12:00:00
draft: false
image:
    url: featured-image.jpg
    attribution: https://source-url.com
authors:
 - chilagrow
tags:
 - community
summary: This guide walks you through components that make up OpenEverest and how they interact.
---

OpenEverest is a cloud-native database platform that simplifies database provisioning and management on Kubernetes. It consists of several key components that work together to provide a seamless experience for users. Here's an overview of how OpenEverest works:

## OpenEverest API Server

The OpenEverest API Server is the central component that exposes a RESTful API for managing database deployments. It handles requests from the CLI and UI, processes them, and interacts with the OpenEverest Operator to perform actions such as provisioning, scaling existing deployments, and configuring monitoring.

## OpenEverest CLI

The OpenEverest CLI is a command-line tool that allows users to interact with the OpenEverest API Server. It provides commands for administrative tasks such as user management.

## OpenEverest UI

The OpenEverest UI is a web-based interface that provides a user-friendly way to manage database deployments. It communicates with the OpenEverest API Server to display information about databases and perform management tasks.

## OpenEverest Operator

The OpenEverest Operator is a Kubernetes Operator that manages the lifecycle of database deployments. It leverages Percona's Kubernetes Operators for MySQL, MongoDB, and PostgreSQL under the hood but provides a unified API and a single pane of glass for managing all three database types.
