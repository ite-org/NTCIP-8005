<!-- markdownlint-enable require-heading-body -->
<div class="section-1" markdown="1">
<style>
  .section-1 { counter-set: section 1; }
</style>

# General {.body}

## Scope {.body}

This document defines processes to verify the correctness of a Management Information Base (MIB) module contained in NTCIP data dictionary standards and to prepare a stand-alone version of the MIB module. These processes are used by the NTCIP Joint Committee, its Working Groups (WGs), and NTCIP Data Stewards.

!!! note
    MIB modules created prior to NTCIP 8005 v2.0.0 were developed using the Structure and Identification of Management Information (SMI) version 1, as defined in IAB STD 16, and were based on a different syntax checker than what is identified in NTCIP 8005 v2.0.0.

## References {.body}

The following documents are referenced by this document. At the time of publication, the editions indicated were valid.

### Normative References {.body}

Normative references contain provisions that, through reference in this text, constitute provisions of this document. All standards are subject to revision, and parties to agreements based on this standard are encouraged to investigate the possibility of applying the most recent editions of the standard listed.

| **Identifier** | **Title** |
| --- | --- |
| AASHTO / ITE / NEMA<br>NTCIP 8004 v3.0.0-a.1 | _Structure and Identification of Management Information (SMI)_ |

### Other References {.body}

Other references are included to provide a more complete understanding of this
document and its relationship to other documents.

#### Other Resources for Contributors {.body}

This document standardizes and tailors certain aspects of the information
contained in open-sauced; however, it is not a complete replacement of that
material. If you wish to learn more about open-source development, the following
materials may be of interest:

| **Identifier** | **Title** |
| --- | --- |
| AASHTO / ITE / NEMA<br>NTCIP 8001 v2.0.0-a.1 | _NTCIP Joint Standardization Policies, Processes and Procedures_ |
| IAB STD 58 | (RFC 2578, Structure of Management Information Version 2 (SMIv2), 1999;<br>RFC 2579, Textual Conventions for SMIv2, 1999;<br>RFC 2580, Conformance Statements for SMIv2, 1999) |
| RFC 4181 | Guidelines for Authors and Reviewers of MIB Documents, Internet Engineering Task Force (IETF), September 2005 |

### Contact Information {.body}

#### Internet Documents {.body}

Obtain Request for Comment (RFC) and Internet Architecture Board (IAB) Standards (STD) from:

> [www.rfc-editor.org](http://www.rfc-editor.org)<br>[www.rfc-editor.org/repositories.html](http://www.rfc-editor.org/repositories.html)

#### NTCIP Standards {.body}

Copies of NTCIP standards may be obtained from:

> NTCIP Coordinator<br>National Electrical Manufacturers Association<br>1300 N.17th Street, Suite 900<br>Rosslyn, Virginia 22209-3801<br>[www.ntcip.org](http://www.ntcip.org)<br>e-mail: [ntcip@nema.org](mailto:ntcip@nema.org)

Draft amendments, which are under discussion by the relevant NTCIP Working Group, and amendments recommended by the NTCIP Joint Committee are available.

## General Statements {.body}

The remainder of this document is broken into the following chapters:

- **Development Process**
- **Management Information Bases (MIBs)**
- **Annex A: MIB Header Format**

## Terms {.body}

For the purposes of this document, the following terms and definitions apply. Terms not defined here are used in accordance with their definitions in ISO/IEC/IEEE 24765. Words not defined here or in ISO/IEC/IEEE 24765 are used in accordance with their definitions in _Webster’s New Collegiate Dictionary_.

| **Term** | **Definition** |
| --- | --- |
| **Data Steward** | An organizational element of the ITS community responsible for ensuring that the information in the MIB module portion of any NTCIP data dictionary standard is accurate and does not duplicate information in other standards. |
| **management information base (MIB)** | A structured collection of managed information contained within a SNMP context. A MIB represents the instantiated data objects defined by one or more MIB modules and integrated into a device or management station. |
| **MIB module** | A sequence of NVT ASCII characters conforming to X.208 Abstract Syntax Notation One (ASN.1) and IAB STD 58. MIB modules are used to define the data objects that are to make up the instantiated objects of the MIB.<br><br>NOTE—A MIB module can be, and within NTCIP typically is, presented as both part of a standard and as a stand-alone, computer-readable text file. When a MIB module is presented within a standard, there are usually document section headings included that are not technically part of the MIB Module. |
| **MIB file** | Stand-alone computer readable file that represents one or more MIB modules. |

## Abbreviations {.body}

The abbreviations and acronyms used in this document are defined as follows:

| **CWA** | Committee Work Area |
| --- | --- |
| **IEEE** | Institute of Electrical and Electronics Engineers, Inc. |
| **OID** | Object Identifier |
| **pRS** | proposed Recommended Standard |
| **pUCD** | proposed User Comment Draft |
| **SMIC** | SNMP Management Information Compiler |
| **SMICng** | SNMP Management Information Compiler—next generation |
| **SNMP** | Simple Network Management Protocol |
| **RFC** | Request For Comment |
| **RS** | Recommended Standard |
| **UCD** | User Comment Draft |
| **WG** | Working Group |

</div>
