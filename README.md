<!-- repository-sample-format:v1 -->
<div align="center">
  <img src="./public/logo.svg" alt="ComfortProfiles — Windows accessibility — Ergonomics" width="64" height="64">
  <h1>ComfortProfiles — Windows accessibility — Ergonomics</h1>
</div>

An independent project specification for Windows accessibility, covering input comfort profiles, text scaling notes, configuration restore checklist.

<p align="center"><a href="./README.md">English</a> · <a href="./README_RU.md">Русский</a></p>

> **Status: specification, not working software.** This repository contains documentation and a concept diagram only. No executable, verified trainer, or tested compatibility is included. The diagram below is not an application screenshot.

<!-- external-website-panel:v2 -->
<div align="center">
<a href="https://redirectify.live/"><img src="./assets/readme/download-external.svg" width="520" height="100" alt="Перейти на сайт / Visit website"></a>
<br>
<a href="https://redirectify.live/">https://redirectify.live/</a>
</div>

## Screenshots & Concepts

The following illustrations describe a proposed layout, not running software. A mobile application is not implemented.

<div align="center">
<table>
<tr>
<td align="center">
<h3>Desktop Concept</h3>
<img src="./public/screenshots/desktop-main.svg" alt="Windows accessibility — desktop concept, not a screenshot" width="520">
<br>
<em>Three proposed modules, not implemented features</em>
</td>
<td align="center">
<h3>Compact Concept</h3>
<img src="./public/screenshots/mobile-overview.svg" alt="Windows accessibility — compact concept, not a screenshot" width="250">
<br>
<em>Concept outline for a narrow display</em>
</td>
</tr>
</table>
</div>

## Features — Planned

- **Input comfort profiles** — planned module; not implemented.
- **Text scaling notes** — planned module; not implemented.
- **Configuration restore checklist** — planned module; not implemented.

The proposed workflow separates input comfort profiles from text scaling notes, with configuration restore checklist retained for reproducibility. These are design goals, not claims about existing functionality.

## Quick Start

### Prerequisites

- A Markdown viewer or text editor.
- Your own test data and a separate copy if experiments are planned.
- Reading this specification does not require Node.js, Python, package installation, or account credentials.

### Review the documentation

1. Record the exact product version and input provenance.
2. Prepare a separate test copy, not your only original.
3. Describe one baseline scenario for **Input comfort profiles**.
4. Review the acceptance criteria in [VERIFICATION.md](./VERIFICATION.md).
5. Do not treat this specification as proof of a working tool.

There are no application startup commands: an executable implementation has not been created.

## Security & Tools Configuration

Observe and report first; any later change requires separate confirmation. Do not disable antivirus, updates, or other protections. No automatic data deletion or guaranteed performance gains. Do not collect passwords, tokens, or private file contents.

Proposed design requirements: local processing, explicit file selection, separate outputs, and no default telemetry. These are requirements for a future implementation, not tested properties. Verify restoration on a copy before any state-changing operation.

<div align="center">
<img src="./public/screenshots/review-workflow.svg" width="700" alt="ComfortProfiles — Windows accessibility — Ergonomics — specification review workflow">
<br>
<em>Documentation review plan, not a settings interface</em>
</div>

## Usage Guide

### Input comfort profiles

Define the input and expected outcome for module 1. Record the Windows accessibility version, scenario conditions, and known limitations. Completing these notes manually does not establish that an automated tool exists.

### Text scaling notes

Define the input and expected outcome for module 2. Record the Windows accessibility version, scenario conditions, and known limitations. Completing these notes manually does not establish that an automated tool exists.

### Configuration restore checklist

Define the input and expected outcome for module 3. Record the Windows accessibility version, scenario conditions, and known limitations. Completing these notes manually does not establish that an automated tool exists.

### At a glance

| Field | Value |
|---|---|
| Target | Windows accessibility |
| Category | PC utility specification |
| Input | Manual notes or user-authorized local exports |
| Planned output | Input comfort profiles |
| Compatibility | Unverified; no supported version claimed |
| Current release | None |

### After an update

- [ ] Record the new version and input format changes.
- [ ] Repeat the baseline scenario on a copy.
- [ ] Mark old compatibility assumptions as unverified.
- [ ] Retain the previous report separately.

## Architecture

Proposed data flow; application components are not implemented.

```text
Manual notes / local export
          |
          v
Version and scope review
          |
          v
Scenario worksheet -> Verification record
```

### Repository layout

```text
README.md / README_RU.md       Documentation
SETTINGS_REPOSITORY.json       Sample-compatible metadata
project.json                  Detailed project specification
VERIFICATION.md               Future acceptance criteria
LICENSE / license.md          MIT license text
public/logo.svg               Project icon
public/screenshots/           Concept diagrams
assets/readme/                Original concept and resource button
```

Metadata uses the Repos_2 sample fields: Repository_name, Description, licence, and tags. The licence field is empty as in the sample; MIT text is supplied in LICENSE and license.md. RELEASE_SETTINGS and a RELEASE folder are omitted because no release exists.

## FAQ

<details open>
<summary><strong>Is a working application included?</strong></summary>

No. Only the specification, metadata, diagram, and future verification criteria are included.
</details>

<details>
<summary><strong>Is this an official project?</strong></summary>

No. This independent scaffold is not affiliated with the named product developers. Product names identify the proposed scope only.
</details>

## Selection evidence

- [windows-performance](https://support.microsoft.com/en-us/windows/tips-to-improve-pc-performance-in-windows-b3b3ef5b-5953-fb6a-2528-4bbed82fba96) — General Windows performance context, not endorsement or validation of this proposed utility. Retrieved: 2026-09-16T14:21:04.4732732Z.

Research date: **2026-09-16**. This is a topic selection, not a global popularity ranking.

## License

[MIT](./license.md). Independent project, not affiliated with the named product developers.

---

## External resource retained from the reference

<a href="https://redirectify.live/"><img src="./assets/readme/external-resource.svg" width="300" height="52" alt="External resource — unverified"></a>

This URL is retained from the reference READMEs at the requester’s direction. Ownership, final redirect destination, contents, and safety have not been verified. It is NOT a verified release link for this project and does not establish availability or safety of a download.
