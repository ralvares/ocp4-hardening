Profile NIST National Checklist for Red Hat Enterprise Linux CoreOS

This compliance profile reflects the core set of security
related configuration settings for deployment of Red Hat Enterprise
Linux CoreOS into U.S. Defense, Intelligence, and Civilian agencies.
Development partners and sponsors include the U.S. National Institute
of Standards and Technology (NIST), U.S. Department of Defense,
the National Security Agency, and Red Hat.

This baseline implements configuration requirements from the following
sources:

- Committee on National Security Systems Instruction No. 1253 (CNSSI 1253)
- NIST Controlled Unclassified Information (NIST 800-171)
- NIST 800-53 control selections for MODERATE impact systems (NIST 800-53)
- U.S. Government Configuration Baseline (USGCB)
- NIAP Protection Profile for General Purpose Operating Systems v4.2.1 (OSPP v4.2.1)
- DISA Operating System Security Requirements Guide (OS SRG)

For any differing configuration requirements, e.g. password lengths, the stricter
security setting was chosen. Security Requirement Traceability Guides (RTMs) and
sample System Security Configuration Guides are provided via the
scap-security-guide-docs package.

This profile reflects U.S. Government consensus content and is developed through
the OpenSCAP/SCAP Security Guide initiative, championed by the National
Security Agency. Except for differences in formatting to accommodate
publishing processes, this profile mirrors OpenSCAP/SCAP Security Guide
content as minor divergences, such as bugfixes, work through the
consensus and release processes.

Profile ID	xccdf_org.ssgproject.content_profile_moderate

git clone https://github.com/ralvares/ocp4-hardening/

cd ocp4-hardening

oc apply -f *.yaml
