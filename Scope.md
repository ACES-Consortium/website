# ACES working-group scope

**Scope version 1.0. Effective 5 November 2026.**
Initial specification: ACES document revision 0.2.1, technical baseline 0.2.
Adoption is recorded in [Notices.md](Notices.md); the supplied file set is identified by SHA256SUMS.txt.

## Purpose

This is the accompanying `Scope.md` for Section 9.13 of the Community Specification License 1.0 in [LICENSE.md](LICENSE.md). It identifies the technical subject matter of the ACES Working Group. It is not a freestanding patent license and does not expand or replace the definitions of Necessary Claims, Contribution, Implementation or Specification in CSL.

## Included subject matter

The Working Group develops interoperable module-boundary specifications for modular robotics and IoT, limited to:

1. **Physical module interfaces.** Mechanical coupling, alignment, retention, contact arrangements, electrical power and grounding interfaces, data contacts, presence detection, interface classes, connection/disconnection behavior, and parallel use of multiple ACES adapters. Safety and environmental provisions are included only insofar as expressly specified for that boundary.
2. **Description and discovery.** Identification, version declaration, module discovery, Electronic Data Sheets, capability descriptions, parameter and result descriptions, telemetry descriptions, power/interface requirements and declared operational constraints.
3. **Execution semantics.** Discovery, description, invocation, acknowledgement, execution state, telemetry, errors and supported configuration at the module boundary, including the identity and correlation information expressly required by those operations.
4. **ACES-specific bindings and profiles.** Mappings of those descriptions and operations to physical and communication transports, but only the ACES-specific requirements actually developed and described in detail in the applicable specification or profile.
5. **Interoperability and conformance.** ACES-defined compatibility rules and conformance requirements necessary to implement the foregoing, including required elements of optional features as addressed by CSL.

## Outside the scope

The Working Group does not standardize system-level orchestration, planning, optimization, AI models, application policy, agricultural or industrial processes, network routing outside the ACES boundary, cloud platforms, storage architecture, or the internal construction and algorithms of a product except to the extent an ACES boundary requirement expressly specifies them.

A product is not brought wholly within scope merely because it implements ACES. An implementer's additional functionality, manufacturing methods, business operations and proprietary extensions are not automatically covered.

Mentioning CAN, CAN-FD, MQTT, Ethernet, OPC UA, HTTP, ISOBUS, TLS, JSON Schema, connector families or another third-party technology does not grant rights in that technology or incorporate all of it into ACES scope. Patent claims for technology only referenced rather than described in detail are subject to the limitations in CSL Section 9.11.

## Applying this scope

This describes the Working Group's field of development, not a declaration that every possible feature in that field has already been specified or patented. Version 0.2 does not fix connector geometry, pin allocation, power classes or specific transport bindings; this scope does not supply those missing technical requirements. Illustrative or non-normative material does not become mandatory by being listed here.

CSL Section 2 distinguishes patent grants for Contributions, Draft Specifications and Approved Specifications. Actual coverage depends on those terms, acceptance and authority, the relevant technical requirements, and any valid exclusions. No third-party patent clearance or universal freedom to operate is represented.

## Changes

Publish proposed scope changes for review under `Governance.md`. Record the adopted scope version, effective date and exact repository revision. Under CSL Section 9.13, changes do not apply retroactively. Preserve earlier scope versions with their corresponding releases. A later scope expansion must not be represented as a new commitment from a former contributor without a proper basis under the applicable terms.
