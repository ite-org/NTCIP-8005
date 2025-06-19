<div class="section-3" markdown="1">
<style>
  .section-3 { counter-set: section 3; }
</style>

# Management Information Bases (MIBs) {.body}

## Syntax Checker {.body}

The standard compiler for checking the syntax of an SNMP MIB file is _smilint_, which is a free tool developed by Frank Strauss of the Technical University of Braunschweig. Information about the project is available at <https://www.ibr.cs.tu-bs.de/projects/libsmi/index.html?lang=de>. The software can be downloaded or used online for free at <https://www.simpleweb.org/ietf/mibs/validate/upload.php>.

## Syntax Checking {.body}

### Compilation Switches {.body}

The tool is used with the maximum level of severity checking (i.e., "6 – Auxiliary notices").

### Output {.body}

When syntax checked, the MIB file result of no “Errors” is required for acceptance. Any "Warnings" are to be corrected or justified in the Steward's report.

## Input File {.body}

The MIB file input to _smilint_ is an "ASCII (Text Only)" file that is consistent with NTCIP 8004.

To convert a Word document to an ASCII file suitable for compilation, follow these steps:

1. Strip all text before and after the MIB (i.e., before the MIB module name and after the "END" statement.)
2. Convert the font within the MIB to a non-proportional type such as Courier New.
3. Replace all tabs with the appropriate number of spaces.
4. Delete any tables or graphics or convert them to ASCII underscore, dashes, or vertical bars.
5. While file viewers with line wrap format the text in the Description Field, users may prefer to add &lt;CR&gt;s and &lt;LF&gt;s to format the Description Field.
6. Customize the header numbering so that entries are preceded by "dash dash."
7. Replace all smart quotes with straight quotes.
8. Save the text as "plain text" (i.e., rather than a Word document).

### MIB Meta Data File {.body}

An NTCIP standard may define more than one MIB module. The MIB modules are converted to separate MIB files. Each MIB file contains a header in the form of comments. The header includes information corresponding to the following:

1. Copyright Statement
2. MIB Distribution Notice

The text of the Copyright Statement and MIB Distribution Notice from the current version of NTCIP 8002 is included. The coverage year of the copyright is updated to the year in which the MIB file was created or modified.

Annex A contains a sample header and the preferred header formatting style.

### Naming Conventions {.body}

NTCIP MIB files and module names are used in multiple applications and for purposes of cross-referencing. Therefore, the following naming convention applies.

1. The File Names for MIB files is of the form:

    &lt;Standard Number&gt;&lt;Version&gt;&lt;Revision&gt;&lt;Designation&gt;.mib

2. If the NTCIP standard designation contains a year of publication, the year of publication is dropped and the specific version number is used. The designation is optional; however, when a standard contains more than one MIB module, each associated MIB file is to be stored as a separate file with a unique designation, which may be the section or annex number or a descriptive name. These examples serve as illustrations:

    1. 1201v0315rMain.mib
    2. 1201v0315rAuxIOv.mib
    3. 1202v0315rAuxIOv02.mib
    4. 2103v0206CHAP.mib
    5. 2103v0206MOD.mib

</div>
