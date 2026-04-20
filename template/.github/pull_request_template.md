Related to #[ISSUE]

## What changed?

<!-- Briefly describe the change and its motivation. -->

<!--
## Additional context
- Notable preceding/dependent PRs
- Additional context/references for reviewers/testers other than referenced issue
-->

## Security impact

<!-- CM-4 (Security & Privacy Impact Analysis): 
     Federal policy requires assessing every change for security impact. 
       * "None expected" is fine for routine changes, so it's pre-filled. 
       * For changes that affect system boundary, data handling, authentication, access
         control, or architecture, you likely need to link to a full Security Impact
         Analysis (SIA) similar to this template: 
         https://docs.google.com/document/d/15Lh4N3grZk-Lq7W2z0Y7u6j4zyUvrljtofXbh-WKpAo/edit 
     Verify that any Security Considerations noted in the linked issue are addressed -->

None expected.

## Checklist

<!-- These items support continuous ATO readiness. The NIST SP 800-53 Rev 5 control
     IDs in the comments show what each item satisfies — removing them may affect
     your compliance posture. -->

- [ ] Tests for these changes added (when possible) <!-- SA-11 Developer Testing · SI-7 Software & Information Integrity -->
- [ ] Relevant docs updated <!-- SA-5 System Documentation · CM-3 Configuration Change Control -->
- [ ] Newly introduced dependencies were reviewed for security posture and compatible licensing, and are actively updated <!-- SR-3 Supply Chain Protection · RA-5 Vulnerability Monitoring -->
- [ ] No new PII or sensitive data handling (or documented) <!-- SI-12 Information Management · PT-2 Authority to Process PII -->

### AI disclosure

<!-- SA-15 (Development Process, Standards, and Tools): GSA policy requires
     transparency about AI tool usage. -->

Check one.

- [ ] I did not use AI tools.
- [ ] I drove, AI tools assisted: I used AI tools, but I was in the driver's seat. (Please indicate when changes were heavily reliant.)
- [ ] AI tools drove, I assisted: These changes were primarily implemented by AI tools, but I can explain, defend, and maintain all the changes.
- [ ] AI tools drove without much assistance: These are changes that would be difficult to maintain without AI tools. (Note that PRs of this nature will be more heavily scrutinized.)

<!-- Optional: note which tools and modes (e.g., Foo completions, Bar chat, Baz coding agent) -->
