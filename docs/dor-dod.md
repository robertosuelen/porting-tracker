# Definition of Ready and Definition of Done

## Definition of Ready
A story only enters Sprint Planning if:
- It is written as "As a , I want  so that ", naming
  one of the three personas.
- It has acceptance criteria that can be verified by someone who did not
  write them.
- It has been estimated by the team.
- It has a parent epic.
- Any dependency on another story is named, or the story is independent.
- It fits in one sprint. If it does not, it is split first.
- Where the UI is not obvious, a wireframe is linked.

## Definition of Done
A story is only Done if:
- Every acceptance criterion is verified.
- The code is merged into main through a pull request reviewed by at least
  one other team member.
- Automated tests cover the acceptance criteria, and CI is green.
- The feature works on a 375px-wide viewport, because Jonas uses a phone
  on site.
- No accessibility regression: keyboard navigation works and form fields
  have labels.
- The README or docs are updated when behaviour changed.
- The Product Owner accepted it in the Sprint Review.

## Definition of Done for the Voyage
- The application is deployed and reachable at a public URL.
- The README explains what it is, who it is for, and how to run it.
- A seeded demo dataset lets a visitor click through without signing up.
