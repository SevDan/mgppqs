# MGPPQS - Open Community Driven Standards

[![Join the chat at https://gitter.im/mgppqs/community](https://badges.gitter.im/mgppqs/community.svg)](https://gitter.im/mgppqs/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Multiplayer Games Product Processes Quality Standards

Suite of community driven standards that contains recommendations for development, quality assuranse, operations and other processes in multiplayers games products & projects.

## Goals
There are a lot of platforms with easy to start requirements (i.e. SA-MP, CR:MP, SA-MP Mobile, MTA, RAGE MP, FiveM etc.), so a lot of development teams starts projects from Proof of Concept and living with it for a long time until some fatal troubles happend. Some products teams has strict internal rules that helps them get stable products based on internal & shared experience, but many rare problems still exists and may be fatal.

MGPPQS should be used as common shared recommendations for different size teams (from small to big) and must be strict description of the best practices for the most cases.

## Standards Common Rules
- Standards can be grouped by folders based on goals, use cases and target spaces.
- Standards should be a text based documents available for editing & viewing with free software (i.e. TXT, DOCX, DOC, XLS, XML, PDF, ODF, CSV etc.)
- Standards should describe common use case for some processes (i.e. product development, quality assuranse etc.) or more specific cases (i.e. MTA game server development with one developer and one manager in team)
- Standards should has common structure with next points:
  1. Title - short description, document number (should be unique for all MGPPQS standards), version: 'MGPPQS <Short Description> #<Unique Number> v.<Version String>' (i.e. 'MGPPQS SA-MP Common Product Development Standard #1 v.0').
  2. Goals - description of main standard goals that contains solving problems description and target audience.
  3. Terms - list of used terms with description
  4. Preconditions - description of predefined requirements for standard implementation and links for other documents & standards
  5. Tags - document keys for search (should represent most important topics and goals)
  6. Body - standard body without common structure (can be different)
  7. Criteria - list of common requirements that can be used as basic criteria of standard implementation (should be described as DoD (Definition of Done))
  8. Links, materials and attachments - other links, materials and attachemnts

## Localization & Internationalization

The main standards language is English (it means the documents can be used as source of truth), but the community can translate it to any languages.

The most important rule for l10n & i18n is to place documents in the same location & add locale suffixes. For instance, if I have doc 'mgppqs-1-common-standard-01.pdf' in English and I want to translate it to Russian, I should place the translated document in the same directory with the name 'mgppqs-1-common-standard-01-ru.pdf'.

## Issues, commits, contribution
### Issues
You can create issues for standards implementations, bug reports, enhancements etc.
Please use common english language and describe your issue as well as you can.
### Commits
Please put number of issue at first in commit messages. (i.e. '#0 Standard #1 implementation')
### Contribution
You can suggest your documents for implementation in issues.
### Branchs
Any incomplete documents should be created in dedicated branchs. Main branch should contains only finished & valid standards. Incomplete documents should be marked with '-incomplete.<buildNumber>' suffix (i.e. 'mgppqs-1-common-01-incomplete-00001.pdf'). After finished, document should be renamed without that suffix to be released in final condition.

## Sertification & Audit
You can use MGPPQS standards for commercial purpose as sertification, audit, consultancy and other. 
Authors are not responsible for any commerical damage or risks, MGPPQS standards are only advisory in nature.
