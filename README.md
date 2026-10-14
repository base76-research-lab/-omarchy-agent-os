# Omarchy Agent OS

An experimental project to build an agentic computer environment alongside [Omarchy](https://github.com/omacom/omarchy).

## Aim

Make it easier for people to shape their own computers and use AI while keeping control of their data. The project prioritizes local models where a machine can run them and aims to adapt its capabilities to different hardware.

## Project state

This repository is at the project-start stage. The goals and development plan are being established; no runtime or agent integration has been selected or shipped. Colibri is one inference-runtime candidate under evaluation, not a project dependency or chosen backend.

## Direction

- Work with Omarchy and keep the user's system understandable and recoverable.
- Adapt model and feature choices to available CPU, memory, storage and GPU.
- Make local and any remote data paths clear to the user.
- Keep permissions, proposed actions and verification visible.
- Test a small end-to-end use case before adding orchestration or background services.

“Works on any computer” is an ambition to investigate, not a compatibility claim. Local models have real memory, storage, speed and licensing limits.

## Development

The project begins with a concrete user scenario, a hardware/runtime survey and a small reversible prototype. Implementation and experiment records will be added here as they are built.

Omarchy is the upstream platform; this repository is an independent experiment and is not an official Omarchy project.

## License

The code in this repository is licensed under the MIT License. Model weights and other external assets have their own licenses; check those separately.
