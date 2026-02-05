# Lumethic

**Forensic image verification and C2PA signing for photographs.**

[![Website](https://img.shields.io/badge/lumethic.com-000000?style=flat-square)](https://www.lumethic.com)
[![C2PA](https://img.shields.io/badge/C2PA-Open_Standard-4A5568?style=flat-square)](https://c2pa.org)
[![CAI Member](https://img.shields.io/badge/Content_Authenticity_Initiative-Member-4A5568?style=flat-square)](https://contentauthenticity.org)

---

## Purpose

Lumethic verifies that photographs represent scenes that existed in front of a camera. The system compares RAW sensor data against published images to detect manipulation and synthetic generation.

Verification requires the original RAW file, the proof that only the photographer has. Only after forensic verification passes does the system sign the image with [C2PA Content Credentials](https://c2pa.org), creating machine-readable proof of authenticity.

---

## Verification Methods

| Method | Analysis |
|--------|----------|
| **Sensor Authenticity** | Validates physics-based characteristics consistent with real camera sensor output. |
| **Visual Consistency** | Compares the submitted photo against a reference generated from RAW sensor data. |
| **Recapture Detection** | Detects whether the photo is an original capture or a photo of a screen or print. |
| **Metadata Validation** | Examines EXIF information for consistency between RAW and output files. |

Each method is independent. All must pass for signing to proceed.

Standard adjustments (exposure, contrast, cropping, rotation) are permitted. Verification checks source and integrity, not aesthetics.

---

## Integration

| Method | Description |
|--------|-------------|
| [Web](https://www.lumethic.com) | Upload and verify |
| [REST API](https://www.lumethic.com/api) | Integrate into existing workflows |
| [Lightroom Plugin](https://www.lumethic.com/plugin-lightroom) | Export with verification |
| [Lumethic Capture iOS App](https://apps.apple.com/de/app/lumethic-capture/id6757165600) | Capture signed photos on device |

---

## Documentation

| Resource | Description |
|----------|-------------|
| [Whitepaper](https://www.lumethic.com/whitepaper) | Verification methodology |
| [Verify, Then Sign](https://www.lumethic.com/articles/verify-then-sign) | Pre-signing verification rationale |
| [What is C2PA?](https://www.lumethic.com/articles/what-is-c2pa) | Content provenance guide |
| [API Reference](https://www.lumethic.com/api) | REST API documentation |

---

## Contact

- [lumethic.com](https://www.lumethic.com)
- hello@lumethic.com

<br>
<p align="left">
  <sub>Developed in Kiel, Germany. © By FX GmbH.</sub>
</p>
