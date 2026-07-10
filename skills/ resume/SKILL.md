---
name: resume
description: Create, optimize and tailor resumes for job applications.
metadata: 
  resumepilot:
    version: 1.0.0
    language: 
      - zh
      - en
    category: resume

---

# Resume Skill

## Overview

Resume Skill is responsible for creating, optimizing, tailoring, and rewriting professional resumes for different job applications and career goals. It focuses exclusively on resume-related tasks and serves as the resume optimization component of ResumePilot-CN. Requests outside the resume domain should be delegated to the appropriate specialized skill.

## Purpose

Help users create, tailor, and optimize resumes for specific career goals and job applications. 

## Scope

### When to Use

Use this skill when the user wants to:

- Create a new resume.
- Improve an existing resume.
- Tailor a resume for a specific job description.
- Rewrite resume content.
- Highlight achievements.
- Optimize resume structure.

### When NOT to Use

Do not use this skill when the user wants to:

- Evaluate ATS compatibility or resume scoring.
- Provide a resume template or design.
- Prepare interview questions or interview simulations.
- Generate cover letters or motivation letters.
- Search for job opportunities.
- Negotiate salary or employment terms.

## Inputs

### Required

- Candidate Profile

### Optional

- Job Information
- Preferences
- Supporting Materials

## Workflow

1. Validate the provided inputs.
2. Identify the user's intent.
3. Determine the optimization mode.
4. Analyze the candidate profile.
5. Analyze the job information (if provided).
6. Generate or optimize the resume.
7. Review the output for consistency and completeness.
8. Return the optimized resume.

## Rules

- Never fabricate facts or achievements.
- Preserve factual information unless the user explicitly requests changes.
- Prioritize clarity, accuracy, and relevance.
- Prefer measurable achievements whenever possible.
- Maintain consistency throughout the resume.

## Outputs

### Primary Output

- An optimized resume.
- A newly generated resume (when requested).

### Optional Output

- Resume improvement recommendations.
- A summary of the major changes.
- Suggested keywords aligned with the target job description.

## Examples

### Trigger Examples

**User:** 帮我优化一下简历。

**Expected:** Use Resume Skill.

---

**User:** 根据这个岗位 JD 修改我的简历。

**Expected:** Use Resume Skill.

---

**User:** Improve my resume for a Product Manager position.

**Expected:** Use Resume Skill.

## Quality Standards

The generated resume should:

- Be factually accurate.
- Match the target role.
- Preserve the user's original experience.
- Highlight measurable achievements.
- Be concise and readable.