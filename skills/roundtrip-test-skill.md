---
name: roundtrip-test-skill
description: skills submitted from local portfolio
author: mickdarling
version: 1.0.0
created: '2025-08-12T00:07:22.325Z'
modified: '2025-08-12T00:07:22.325Z'
tags: []
dependencies: []
custom: {}
languages: []
complexity: beginner
domains: []
prerequisites: []
parameters: []
examples: []
proficiency_level: 0
id: skills_roundtrip-test-skill_2025-08-12T00-07-22-484Z
type: skills
---

# Roundtrip Test SkillThis skill is specifically designed to test the complete DollhouseMCP collection workflow:1. Download from collection repository2. Modify locally3. Submit to GitHub portfolio  4. Re-submit to collection## PurposeYou are a test skill that helps validate the entire collection submission workflow. Your role is to:- Be downloaded from the collection- Be modified by users- Be uploaded to their GitHub portfolio- Be re-submitted to the collection## Test Scenarios### Scenario 1: Basic Roundtrip1. User downloads this skill from collection2. User modifies the version number or description3. User submits to their portfolio4. User optionally submits back to collection### Scenario 2: Enhanced Roundtrip1. User downloads this skill2. User adds new capabilities or parameters3. User changes the name slightly e.g., Enhanced Roundtrip Test4. User submits to portfolio with auto-submit enabled5. New issue created in collection showing the enhancement## Validation ChecklistWhen testing with this skill, verify:- [ ] Download from collection works- [ ] Local modifications are preserved- [ ] Portfolio upload succeeds- [ ] GitHub portfolio shows correct content- [ ] Collection submission creates proper issue- [ ] Issue contains correct metadata- [ ] Labels are applied correctly- [ ] Author attribution is correct## Test ParametersThese parameters can be modified during testing:- test_mode: basic  enhanced  stress- iteration: Track which test run this is- modified_by: Username of tester- modification_date: When the test was run- test_results: Success/failure status## Expected Behavior### On Download- Skill appears in local portfolio/skills directory- Metadata is preserved- Content is readable and valid### On Modification- Changes are saved locally- Version number can be updated- New parameters can be added### On Portfolio Upload- File uploaded to GitHub portfolio repository- Correct path: skills/roundtrip-test-skill.md- Commit message mentions the skill name### On Collection Submission- Issue created with title: [skills] Add Roundtrip Test Skill by @username- Labels: contribution, pending-review, skills- Issue body contains portfolio URL- Metadata shown in formatted code block## Test Instructionsbash# Step 1: Download this skill simulate with copycp library/skills/roundtrip-test-skill.md /.dollhouse/portfolio/skills/# Step 2: Modify locally add a timestampecho Modified: [current date]  /.dollhouse/portfolio/skills/roundtrip-test-skill.md# Step 3: In Claude Desktop, submit to portfoliosubmit_content Roundtrip Test Skill# Step 4: Check portfolio# Visit: https://github.com/username/dollhouse-portfolio/blob/main/skills/roundtrip-test-skill.md# Step 5: If auto-submit enabled, check collection# Visit: https://github.com/DollhouseMCP/collection/issues## Success MetricsThe roundtrip is successful when:1. ✅ Skill moves through all stages without errors2. ✅ Modifications are preserved throughout3. ✅ GitHub repositories update correctly4. ✅ All metadata remains intact5. ✅ User can track the skills journey## Notes- This is a test skill - not for production use- Can be safely deleted after testing- Multiple versions can exist for different test runs- Consider using timestamps in names for uniqueness---Test skill for DollhouseMCP collection workflow validation
