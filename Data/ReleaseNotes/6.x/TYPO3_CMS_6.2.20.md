Release Notes for TYPO3 CMS 6.2.20
==================================

This document contains information about TYPO3 CMS 6.2.20 which was
released on April 12th, 2016.

News
----

This release is a combined bug fix and security release.

Notes
-----

Find more details in the security bulletins:

-   <https://typo3.org/teams/security/security-bulletins/typo3-core/typo3-core-sa-2016-009/>
-   <https://typo3.org/teams/security/security-bulletins/typo3-core/typo3-core-sa-2016-010/>
-   <https://typo3.org/teams/security/security-bulletins/typo3-core/typo3-core-sa-2016-011/>
-   <https://typo3.org/teams/security/security-bulletins/typo3-core/typo3-core-sa-2016-012/>

Download
--------

<https://typo3.org/download/>

MD5 checksums
-------------

    f4ab1d7d5fb26a24e616d2c5a0036110  typo3_src-6.2.20.tar.gz
    43b4c85227edd67b40c71a05d2aae9eb  typo3_src-6.2.20.zip

SHA256 checksums
----------------

    309eb79538187979ee2fcb6aebeabd1e8a2324b4d3161740a5a1f11f4c94f85b  typo3_src-6.2.20.tar.gz
    85a3f6f0be67d009a98251816f15a71e1a7c03da9fd1456eea2636f546afe9b7  typo3_src-6.2.20.zip

Upgrading
---------

The [usual upgrading
procedure](https://docs.typo3.org/typo3cms/InstallationGuide/) applies.
No database updates are necessary.\
It might be required to clear all caches; the “important actions”
section in the TYPO3 Install Tool offers the accordant possibility to do
so.

Changes
-------

Here is a list of what was fixed since
[6.2.19](TYPO3_CMS_6.2.19 "wikilink"):

    2016-04-12  efbf8a9                  [RELEASE] Release of TYPO3 6.2.20 (TYPO3 Release Team)
    2016-04-12  1fcfd5b  #75055          [SECURITY] Disallow login with empty password (Nicole Cordes)
    2016-04-12  5a8e0a1  #28175          [SECURITY] Limit user access in workspace previews (Nicole Cordes)
    2016-04-12  c6dcf83  #51908          [SECURITY] Prevent XSS in ElementBrowser (Markus Klein)
    2016-04-12  ef368ac  #75164          [SECURITY] Prevent XSS in SelectMultipleSideBySideElement (Nicole Cordes)
    2016-04-12  e7ca585  #73459          [SECURITY] Fix arbitrary file disclosure in form extension (Steffen Müller)
    2016-04-12  ab32091  #75022          [BUGFIX] Load XML files of Extension Manager properly (Andreas Fernandez)
    2016-04-07  ab3cc83  #74131          [BUGFIX] WinCache 2.0 and newer have no opcode cache (Alexander Opitz)
    2016-04-06  f5219a6  #75423          [TASK] Allow installation of composer installers 1.2.x (Helmut Hummel)
    2016-04-04  08ef6cd  #69773          [BUGFIX] Warning when clearing all caches from within install tool (Bernhard Kraft)
    2016-03-31  d5d3832  #75273          [TASK] Loosen version constraint for TYPO3 CMS Composer Installers (Christian Opitz)
    2016-03-31  ccea306  #73631          [BUGFIX] only trim leading slash from section name (Daniel Neugebauer)
    2016-03-30  c36eb54  #75156          [BUGFIX] Add reference count to delete message (Gianluigi Martino)
    2016-03-29  4b2594f  #75283          [BUGFIX] Use proper quotation in phpdoc of ExtensionManagementUtility::addService() (Andreas Fernandez)
    2016-03-29  d767d59  #75287          [BUGFIX] Fix typo in BooleanNode exception message (Sascha Egerer)
    2016-03-23  297a828  #75242          [BUGFIX] Use `modTSconfig` for default language label, if set (Andreas Fernandez)
    2016-03-12  c5cec73  #72606          [BUGFIX] Prevent TYPO3.settings in ajax requests (Nicole Cordes)
    2016-03-11  e9c6fb9  #74815          [TASK] Add unit tests for TYPO3SEARCH markers (Tymoteusz Motylewski)
    2016-03-10  7e934ec  #74508          [BUGFIX] Load XML files of t3editor properly (Andreas Fernandez)
    2016-03-06  25ee28e  #72225          [BUGFIX] Workspace page previews collide with generated preview links (Oliver Hader)
    2016-03-05  9db88b5  #74127          [BUGFIX] Ensure t3d compatibility for supported TYPO3 version (Nicole Cordes)
    2016-03-04  3fbe9cd  #70373          [BUGFIX] Adjust UserAgent checks in RTE to detect Edge correctly (Benjamin Kott)
    2016-03-04  54e3a4d  #71094          [TASK] Keep selected page active after save & close (Gianluigi Martino)
    2016-03-04  5ecde7c  #69346          [TASK] EXT:form - Update and optimize documentation (Björn Jacob)
    2016-03-03  b389089  #72886          [TASK] Add info about Apache version when using mod_filter (Eric Chavaillaz)
    2016-02-25  8060388  #73243          [BUGFIX] Stage buttons shown in frontend without user being repsonsible (Oliver Hader)
    2016-02-23  5bea0c5                  [TASK] Set TYPO3 version to 6.2.20-dev (TYPO3 Release Team)


