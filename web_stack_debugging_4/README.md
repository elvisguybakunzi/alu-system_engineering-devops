# Web stack debugging project #4

## Web Server Debugging with Nginx

Welcome to the Web Server Debugging with Nginx project. In this task, we address performance issues in a web server setup featuring Nginx. We will utilize ApacheBench to benchmark the server and identify the cause of failed requests. The goal is to optimize the server configuration to achieve optimal performance and eliminate failed requests.

## Table of Contents

1. [Introduction](#introduction)
2. [Initial Benchmark](#initial-benchmark)
3. [Debugging Steps](#debugging-steps)
   - [1. Analysis of ApacheBench Results](#1-analysis-of-apachebench-results)
   - [2. Applying Puppet Manifests](#2-applying-puppet-manifests)
4. [Result](#result)
5. [Conclusion](#conclusion)

## Introduction

In this project, we encountered performance issues in a web server setup using Nginx. The server was experiencing a significant number of failed requests, impacting its overall performance. Our goal was to identify the root cause of these issues and apply necessary optimizations to achieve better performance.

## Initial Benchmark

We began by running ApacheBench to simulate HTTP requests and benchmark the server's performance. The initial benchmark showed that out of 2000 requests, 943 requests failed, indicating a problem with the server configuration.

## Debugging Steps

### 1. Analysis of ApacheBench Results

Upon analyzing the ApacheBench results, we observed that the server was returning a large number of failed requests. This pointed towards potential configuration issues with Nginx that were causing the server to struggle under load.

### 2. Applying Puppet Manifests

We used Puppet, a configuration management tool, to apply necessary changes to the Nginx configuration. The Puppet manifests were designed to optimize the server settings, improve resource utilization, and enhance performance.

The Puppet manifests were executed using the following command:
```bash
puppet apply <puppet_manifest_filename>
