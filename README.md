# GitHub Workflows

**Purpose:** Automate tasks such as testing, building, and deploying your Node.js + TypeScript project whenever you push code to GitHub.

## Key Points to Cover in Documentation

* ## Introduction to GitHub Actions

  * What it is and why use it
  * CI/CD automation concept

* ## Workflow Basics

  * Workflow YAML file location: .github/workflows/
  * name, on, jobs, steps sections

* ## Common Workflow Triggers

  * push, pull_request, schedule, workflow_dispatch

* ## Job and Steps

  * Job: a collection of steps running on a specific runner
  * Steps: commands or actions executed in the job

* ## Actions

  * Prebuilt vs custom actions
  * Examples: actions/checkout, actions/setup-node

* ## Using Secrets

  * Storing sensitive info like API keys

* ## Example Workflow for Node.js + TypeScript

  * Install Node.js
  * Install dependencies
  * Run tests
  * Build project

* ## Advantages

  * Automation of repetitive tasks
  * Faster feedback on code changes
  * Easy deployment pipelines
  * Integration with GitHub ecosystem
