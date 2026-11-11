# Owner Decisions

Questions and decisions that require the project owner's input.

## 1. CONTRIBUTING.md — Template Cleanup

The current CONTRIBUTING.md contains significant template/placeholder text from other projects (Celery code of conduct, jQuery Foundation CLA, Travis CI security email, etc.). Should this be cleaned up to be specific to the Awesome-RCE-techniques project?

**Recommendation:** Rewrite with project-specific content: actual security contact, actual contribution steps, remove references to unrelated projects.

## 2. GLPI Technique — External Images

The GLPI technique README uses external image links (imgur, GitHub user-content) instead of local images like other techniques. Should these be downloaded and stored locally for consistency and long-term availability?

**Recommendation:** Download and store locally in an `imgs/` directory within the technique folder.

## 3. CONTRIBUTING.md — Code of Conduct Reference

The Code of Conduct section references "Celery community" instead of this project. Should it be updated?

**Recommendation:** Replace with a reference to this project's community, or adopt a standard CoC (e.g., Contributor Covenant).

## 4. Missing Test Environments

Some techniques are missing Docker test environments:
- GLPI shellcommand plugin RCE
- Apache Tomcat CVE-2017-12615

Should test environments be created for these?

## 5. Twitter/X Badge

The README links to Twitter/X which has been renamed. Should the badge be updated to reflect the current branding?
