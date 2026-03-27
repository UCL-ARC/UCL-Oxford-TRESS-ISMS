# Overview

This process egresses data out of a TRE Project space. It allows a user with the required permissions to request data to be egressed out of the TRE. A review of the egress request happens, and a user with the required permissions can downlaod the file(s) if the request is approved. This process is owned by the ARC TRE Environment Owner.

## 5 Safes Link

**Safe outputs**: only safe, non-sensitive data is egressed from the TRE.

## Workflow

![Egress_swimlaneview](https://github.com/UCL-ARC/tre-design/blob/4f39309c95c5390c323c790cbb67b680c3f57c73/Diagrams/tre-processes-Egress.drawio.png)

In the above example the egress preparation is done entirely within the Project boundary and remains the responsibility of the users in the Project Roles Group.

# Process
## Purpose

This process ensures that only safe outputs are egressed for the TRE. For Projects with >2 members require 2 approvals, though even for Projects with <2 members, the process ensures careful review of all material before it can be copied out of the TRE.

## Scope

All data egress from any UCL TRE Project is within the scope of the ISMS and this process.

## Responsibilities
- Information Asset Owner: defines the requirements for preparing and testing data for egress (how to make the output safe and any statistical checks required).
- Approved Researcher: follows procedure for safely egressing results data / output from the TRE.
- Output Checker: confirms outputs are safe and approves egress.
- Egresser: downloads the results data / output file(s).

## Prerequisites

- Egresser (downloader) and Ingresser (uploader) must be Approved Researchers before they can be assigned these Project roles.
- Egress Requester and Egress Checker both need a User Desktop in order to perform their respective roles. In addition, they must Approved Researchers.

## Steps

1. Approved Researcher prepares an output.
2. Approved Researcher performs statistical checks to ensure output is "safe" and justifies any deviations.
3. Approved Researcher creates a export payload.
4. Approved Researcher with Egress Requester role copies files to output folder.
5. Output Checker checks outputs are safe.
6. Output Checker approves output via web UI.
7. Output Checker notifies Researcher.
8. Egresser (likely to be original researcher requesting output) downloads file(s).
