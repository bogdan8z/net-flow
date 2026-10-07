Act as a Staff .NET Engineer.

Execute the workflow below.

Step 1:
Run the process described in
01-requirements.prompt.md

Step 2:
Use the output of Step 1 as input for
02-architecture.prompt.md

Step 3:
Use the output of Step 2 as input for
03-implementation.prompt.md

Step 4:
Use the generated implementation as input for
04-unit-tests.prompt.md

Step 5:
Use the generated implementation as input for
05-integration-tests.prompt.md

Step 6:
Review the generated solution according to
06-code-review.prompt.md

Step 7:
Review the generated solution according to
07-security-review.prompt.md

Step 8:
Review the generated solution according to
08-performance-review.prompt.md

Step 9:
Generate documentation according to
09-documentation.prompt.md

Step 10:
Generate delivery artifacts according to
10-delivery.prompt.md

Mandatory:
When a new run starts, create a new subfolder ( inside the features folder) named feat-AAAA where AAAA is 0001, 0002, 0003, ... 9999.
Use the next available numeric suffix, never reuse an existing feature folder.
Inside the new feat-AAAA folder, save the output result files for these steps: 1-requirements.md, 2-architecture.md, 6-review.md, 7-security-review.md, 8-performance-review.md, 9-documentation.md, 10-pr-summary.md.
If a feature folder already exists, do not overwrite it; create the next unused feat-AAAA folder instead.



Requirement:
{{REQUIREMENT}}
