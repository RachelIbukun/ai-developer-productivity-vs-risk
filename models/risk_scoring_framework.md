# Risk Scoring Framework

## Purpose

This framework provides an initial structure for comparing productivity gains and security risks in AI-assisted software development tasks.

## Productivity Score

Productivity may be measured using:

* Task completion time
* Number of successful task completions
* Developer effort required
* Number of iterations required
* Time spent debugging

## Security Risk Score

Security risk may be measured using:

* Number of vulnerabilities
* Severity of vulnerabilities
* Presence of insecure defaults
* Dependency vulnerabilities
* Misconfigurations
* Missing authentication or authorisation
* Poor secrets handling
* Weak logging or monitoring

## Example Scoring Model

| Score | Meaning                   |
| ----- | ------------------------- |
| 1     | Low risk                  |
| 2     | Minor weakness            |
| 3     | Moderate security concern |
| 4     | High-risk vulnerability   |
| 5     | Critical issue            |

## Combined Assessment

A task should not be considered successful only because it was completed quickly.

A stronger assessment should ask:

1. Was the task completed correctly?
2. Was it completed securely?
3. Were vulnerabilities introduced?
4. How much effort would be required to remediate the output?
5. Would a human reviewer be likely to detect the issue?

## Draft Formula

Security Debt Score = Vulnerability Severity + Remediation Effort + Likelihood of Missed Review

## Status

This is an initial framework and will be refined as experimental work develops.
