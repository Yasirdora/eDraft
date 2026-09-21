# Security policy

## Supported versions

No version of eDraft has been publicly released. There is no shipped build to
patch, and no released version receives security updates.

The private channel below exists now, before it is needed.

## Reporting a vulnerability

**Please do not report security issues in a public issue.**

Write to [edraft@ysr.design](mailto:edraft@ysr.design) with:

- what the issue is, and what it affects;
- the steps that reproduce it, or a proof of concept;
- the version, the platform, and how you obtained the build;
- how you would like to be credited, if at all.

You will get a reply telling you what happens next. If a fix is needed, you will
be told when it is in, and when the details may be discussed publicly.

## Scope

In scope, once a build exists:

- the eDraft applications, on any platform they are released for;
- the handling of a document file, including anything a hostile file could
  cause on being opened;
- anything that would let a script leave the writer's machine.

In scope today, in this repository:

- the [example files](examples) — a sample file that behaves maliciously when
  opened is a security report, not a documentation issue.

Out of scope:

- the application source being private, which is a product decision;
- reports produced by automated scanners with no demonstrated impact;
- findings in third-party software that eDraft does not ship.

## Language

Enquiries in English, please.
