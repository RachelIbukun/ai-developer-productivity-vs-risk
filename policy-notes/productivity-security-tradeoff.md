# Productivity vs Security Trade-off

## Purpose

This note outlines the central policy and governance concern behind this project: AI-assisted software development may improve productivity while also creating hidden security risks.

## Core Problem

Organisations adopting AI coding tools often measure success through productivity indicators such as:

* Faster delivery
* Reduced engineering effort
* More code produced
* Faster troubleshooting
* Lower development costs

However, these metrics may not capture downstream risks such as:

* Vulnerabilities introduced into code
* Poor dependency choices
* Weak security configurations
* Increased technical debt
* Reduced human review quality
* Over-reliance on AI-generated outputs

## Policy Question

How should organisations evaluate AI-assisted software development if the benefits appear immediately but the security costs emerge later?

## Why This Matters

If AI-assisted development increases short-term output but creates long-term security debt, organisations may make adoption decisions based on incomplete evidence.

A responsible deployment framework should consider both:

1. Productivity gains
2. Security and governance costs

## Initial Framework

A more balanced assessment of AI-assisted development should include:

| Area           | Example Measure                                       |
| -------------- | ----------------------------------------------------- |
| Productivity   | Completion time, delivery speed, developer effort     |
| Security       | Vulnerability count, severity, exploitability         |
| Governance     | Human review, accountability, auditability            |
| Resilience     | Ability to detect, respond, and recover from failures |
| Long-term cost | Remediation effort, maintenance burden, security debt |

## Working View

AI-assisted software development should not be assessed only by how much faster developers can complete tasks. It should also be assessed by how securely, reliably, and responsibly those tasks are completed.

## Next Steps

The next step is to develop a simple scoring model that compares productivity gains against security risk indicators.
