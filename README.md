# Week 5 Whitespace Practical
## Docker and Responsible AI Use

Welcome to your Week 5 whitespace practical.

In this guided, self-directed session, you will explore Docker containers, build a custom website image and investigate persistent storage.

You may use an AI/LLM tool to support your learning, but AI use is optional. If you choose to use AI, you will practise evaluating its suggestions, verifying results and acknowledging its assistance.

No prior Docker experience is required.

> Educational use
>
> This practical uses simplified examples for learning on an authorised computer. The examples are not production deployment instructions. Use only your own practice resources, follow the school’s policies and review commands before running them.

---

## Contents

- [1. Learning Outcomes](#1-learning-outcomes)
- [2. Practical Overview](#2-practical-overview)
- [3. Submission Requirements](#3-submission-requirements)
- [4. Working Safely](#4-working-safely)
- [5. Optional AI Use and Your Responsibilities](#5-optional-ai-use-and-your-responsibilities)
- [Guided Activities](#guided-activities)
- [6. G1 — Install or Verify Docker Desktop](#6-g1--install-or-verify-docker-desktop)
- [7. G2 — Prepare the Workspace and Download an Image](#7-g2--prepare-the-workspace-and-download-an-image)
- [8. G3 — Run a Containerised Website](#8-g3--run-a-containerised-website)
- [9. G4 — Inspect and Manage a Container](#9-g4--inspect-and-manage-a-container)
- [10. G5 — Build a Custom Website Image](#10-g5--build-a-custom-website-image)
- [11. G6 — Demonstrate Named-Volume Persistence](#11-g6--demonstrate-named-volume-persistence)
- [12. Small Applied Practical Assessment](#12-small-applied-practical-assessment)
- [13. Reflection](#13-reflection)
- [14. AI/LLM Usage Declaration](#14-aillm-usage-declaration)
- [15. Assessment Criteria](#15-assessment-criteria)
- [16. Troubleshooting and Using AI Effectively](#16-troubleshooting-and-using-ai-effectively)
- [17. Final Submission Checklist](#17-final-submission-checklist)
- [18. After Capturing Your Evidence](#18-after-capturing-your-evidence)
- [Official Documentation](#official-documentation)

---

## 1. Learning Outcomes

By the end of this practical, you should be able to:

1. Install or verify Docker Desktop on Windows.
2. Distinguish between an image and a container.
3. Run a containerised website and access it through a browser.
4. Inspect, stop, start and remove a practice container.
5. Build a custom image using a Dockerfile.
6. Demonstrate that data in a named volume remains available after a container is removed.

If you choose to use an AI/LLM tool during this practical, you should also be able to:

7. Ask an AI/LLM a focused technical question.
8. Evaluate an AI response for accuracy, suitability and safety.
9. Verify a suggestion through documentation and your own execution.
10. Acknowledge AI assistance accurately.

---

## 2. Practical Overview

| Item | Details |
| :--- | :--- |
| Module session | Week 5 whitespace practical |
| Format | Guided self-learning activities followed by a small applied practical assessment |
| Total time | 180 minutes |
| Operating environment | Windows with Docker Desktop using Linux containers |
| Terminal | PowerShell |
| Text editor | Notepad |
| Other tools | Web browser and Microsoft Word |
| Optional tool | An AI/LLM tool |
| Guided activities | G1–G6 |
| Applied assessment | Parts A and B |
| Submission | One Word document |
| Evidence | Screenshots of your own execution |
| Written components | Approximately 100–150 words of reflection and a brief AI/LLM usage declaration |

### Required Route

```text
Prepare your Word document
            ↓
G1: Install or verify Docker Desktop
            ↓
G2: Prepare the workspace and download an image
            ↓
G3: Run a containerised website
            ↓
G4: Inspect and manage a container
            ↓
G5: Build a custom image and check your understanding
            ↓
G6: Demonstrate named-volume persistence
            ↓
Complete assessment Parts A and B
            ↓
Finish your reflection, declaration and submission checks
```

### Time Allocation

| Activity | Minutes |
| :--- | ---: |
| G1: Installation and readiness checks | 45 |
| G2: Workspace and image preparation | 10 |
| G3: Run a containerised website | 15 |
| G4: Inspect and manage a container | 15 |
| G5: Build a custom image and complete the learning checkpoint | 30 |
| G6: Demonstrate persistent data | 20 |
| Assessment Part A: Custom website | 15 |
| Assessment Part B: Persistent message | 15 |
| Reflection, declaration and submission checks | 15 |
| Total | 180 |

Screenshot capture, troubleshooting and any optional AI consultation are included within these allocations.

> Installation time can vary because of downloads, restarts, compatibility and permissions. Work within the allocated session, use the troubleshooting guidance and document incomplete work honestly.

---

## 3. Submission Requirements

Submit one Word document containing:

1. Student details.
2. Screenshot evidence for G1–G6.
3. Screenshot evidence for assessment Parts A and B.
4. A reflection of approximately 100–150 words.
5. A brief AI/LLM usage declaration stating whether you used AI.

No separate report, scripts, source files, command transcript, presentation, video, AI conversation history or ZIP file is required.

### Prepare Your Document

Open Microsoft Word and create these headings:

```text
Week 5 — Docker and Responsible AI Use

Student Details

G1 — Installation and Readiness
G2 — Workspace and Image
G3 — Containerised Website
G4 — Container Lifecycle
G5 — Custom Website Image
G6 — Named-Volume Persistence

Assessment Part A — Custom Website
Assessment Part B — Persistent Message

Reflection
AI/LLM Usage Declaration
```

Include your name, student ID and class under Student Details.

Save using the school’s naming convention. If none is specified, use:

```text
StudentID_Week5_Docker_Practical.docx
```

Save regularly throughout the practical.

### Screenshot Expectations

- Capture your own commands and results.
- Keep relevant text readable.
- Include the browser address when showing a website.
- Include relevant container, image or volume names.
- Use multiple screenshots when one image cannot show the required sequence clearly.
- Crop unrelated private information without changing the meaning of the evidence.
- Use screenshots from actual execution, not generated or reconstructed output.

Short captions are optional. A separate written explanation for every screenshot is not required.

---

## 4. Working Safely

During this practical:

- Use only a computer and account you are authorised to use.
- Follow the school’s installation, security and AI-use policies.
- Use student initials in website content and stored messages.
- Keep passwords, tokens and unrelated personal information out of files, screenshots and AI prompts.
- Review commands that remove containers or data before running them.
- Capture required evidence before removing resources.
- Keep practice websites local using the port mappings provided.
- Avoid broad cleanup commands, factory resets or changes to security settings as routine troubleshooting.

Use an ordinary PowerShell window for practical commands. Use elevated permissions only when an authorised installation or system-configuration step requires them.

---

## 5. Optional AI Use and Your Responsibilities

Using an AI/LLM tool is optional. You may complete this practical using the guide and official documentation without using AI.

If you choose to use AI, use it to support your understanding or investigation. Review its responses, check important claims and verify suggested actions before relying on them.

You are responsible for understanding the commands you run and submitting evidence of your own execution, whether or not you use AI.

### Workflow if You Use AI

```text
Make a prediction or identify a question
                    ↓
Ask a focused question
                    ↓
Review the response
                    ↓
Check its suitability and safety
                    ↓
Verify an important claim
                    ↓
Acknowledge the assistance
```

### Responsibilities if You Use AI

| Responsibility | What it means here |
| :--- | :--- |
| Ask clearly | Include the relevant activity, environment, command and actual result. |
| Protect information | Remove passwords, tokens, student identifiers and unrelated private content before sharing. |
| Review critically | Treat the response as a suggestion to evaluate. |
| Understand actions | Check what a command changes and whether it removes data or affects security. |
| Verify independently | Compare important claims with documentation and your own observed execution. |
| Preserve authenticity | Submit evidence from your own work. |
| Acknowledge assistance | State the tool, purpose and verification method. |

No AI conversation screenshots or transcripts are required.

If you do not use AI, simply state this in your declaration. You do not need to explain or justify that choice.

---

## Guided Activities

Complete activities G1–G6 in order. Each activity includes instructions, an expected result and the screenshot evidence to capture.

These activities prepare you for the applied assessment in Section 12.

### Activity Summary

| Activity | Focus | Expected Outcome | Time |
| :--- | :--- | :--- | ---: |
| G1 — Installation and Readiness | Install or verify Docker Desktop and run a test container | Docker connects to its engine and runs `hello-world` | 45 minutes |
| G2 — Workspace and Image | Create the working folders and download `nginx:alpine` | Your workspace is ready and the image is available locally | 10 minutes |
| G3 — Containerised Website | Run Nginx with a local port mapping | The welcome page is accessible in your browser | 15 minutes |
| G4 — Container Lifecycle | Inspect logs, stop, start and remove a container | You can distinguish between restarting an existing container and creating a new one | 15 minutes |
| G5 — Custom Website Image | Create HTML, write a Dockerfile, build an image and check your understanding | Your custom website displays your initials, and you have verified an explanation using documentation and execution | 30 minutes |
| G6 — Named-Volume Persistence | Store a message and retrieve it after replacing a container | The original message remains available through the same named volume | 20 minutes |
| Total | | | 135 minutes |

The remaining 45 minutes are allocated to assessment Parts A and B, your reflection, the AI declaration and submission checks.

### How to Complete Each Activity

1. Read the activity before running its commands.
2. Run commands in PowerShell unless instructed otherwise.
3. Compare your actual result with the expected result.
4. If the result differs, use Section 16 to investigate one check at a time.
5. Capture the required screenshots while the relevant results are visible.
6. Paste the screenshots under the matching heading in your Word document.
7. Save your document before continuing.

### Optional AI Support

You may use AI to explain a command, check a prediction or investigate an unexpected result.

If you do, review suggestions before applying them, protect private information and acknowledge the assistance accurately.

The learning checkpoint in G5 can be completed with or without AI.

### Before You Begin

- [ ] I have read the safety instructions.
- [ ] I understand that AI use is optional and that responsibilities apply if I use it.
- [ ] My Word document is prepared with headings for G1–G6.
- [ ] I know where to place my screenshot evidence.
- [ ] I will use my initials in website content and stored messages.
- [ ] I understand that incomplete work should be documented honestly.

Continue with G1 below.

---

## 6. G1 — Install or Verify Docker Desktop

Time allocation: 45 minutes.

### 6.1 Check the Installation Requirements

Open the official installation guide:

[Install Docker Desktop on Windows](https://docs.docker.com/desktop/setup/install/windows-install/)

Check the current requirements for your:

- Windows version.
- Processor architecture.
- Memory.
- WSL configuration.
- Virtualisation support.

If Docker Desktop is already installed, proceed to Section 6.3.

### 6.2 Install Docker Desktop

1. Download the appropriate installer from the official page.
2. Run the installer.
3. Follow the current installation instructions.
4. Use the WSL 2 backend where appropriate for your authorised environment.
5. Complete any required restart.
6. Open Docker Desktop.
7. Review the displayed terms and follow the school’s licensing arrangements.
8. Wait for the Docker engine to become ready.

Installation screens may vary by version. Follow the official instructions rather than expecting every screen to match this guide exactly.

If installation is blocked by permissions or compatibility, capture the actual message. Do not attempt to bypass the restriction.

### 6.3 Check WSL if Needed

Open PowerShell:

```powershell
wsl --version
```

If Docker Desktop reports a WSL problem, consult Section 16 and the official installation instructions.

Only install or update system components when authorised.

### 6.4 Verify Docker

Open a new PowerShell window:

```powershell
docker version
```

Expected result:

- Client information appears.
- Server information appears.
- No engine-connection error is shown.

Next, run:

```powershell
docker run --rm hello-world
```

On its first use, Docker may download the image before running it.

Expected result: a message containing:

```text
Hello from Docker!
```

The `--rm` option removes this temporary container after it finishes.

### Evidence for G1

Capture:

- Successful `docker version` output showing Client and Server information.
- The successful `hello-world` result.

Place the screenshots under G1 in your Word document.

### Readiness Checkpoint

Continue when Docker can connect to its engine and run the test container.

If it cannot, use Section 16. Record any unresolved limitation honestly.

---

## 7. G2 — Prepare the Workspace and Download an Image

Time allocation: 10 minutes.

### 7.1 Create Your Workspace

In PowerShell:

```powershell
New-Item -ItemType Directory -Path "$HOME\DOP-Docker" -Force
Set-Location "$HOME\DOP-Docker"
New-Item -ItemType Directory -Path .\site, .\assessment -Force
```

Check your location and folders:

```powershell
Get-Location
Get-ChildItem
```

Expected structure:

```text
DOP-Docker/
├── site/
└── assessment/
```

Keep using this PowerShell window.

If you open another one later, return to the workspace:

```powershell
Set-Location "$HOME\DOP-Docker"
```

### 7.2 Download the Website Image

```powershell
docker pull nginx:alpine
```

Then list it:

```powershell
docker image ls nginx
```

### Key Terms

| Term | Meaning in this practical |
| :--- | :--- |
| Image | The packaged template used to create containers |
| Container | An instance created from an image |
| `nginx` | The web server used for the website activities |
| `alpine` | The image tag selected for this practical |

### Evidence for G2

Capture:

- The workspace folders.
- The image listing showing `nginx` with the `alpine` tag.

Place the screenshots under G2.

---

## 8. G3 — Run a Containerised Website

Time allocation: 15 minutes.

### 8.1 Start the Container

```powershell
docker run -d --name dop-demo -p 127.0.0.1:8080:80 nginx:alpine
```

### Understand the Command

| Component | Purpose |
| :--- | :--- |
| `docker run` | Creates and starts a container |
| `-d` | Runs it in the background |
| `--name dop-demo` | Gives the container a recognisable name |
| `-p 127.0.0.1:8080:80` | Maps local host port 8080 to container port 80 |
| `nginx:alpine` | Selects the image |

### 8.2 Check the Running Container

```powershell
docker ps
```

Look for:

- Container name: `dop-demo`.
- Image: `nginx:alpine`.
- A running status.
- The port mapping.

### 8.3 Open the Website

In your browser, visit:

```text
http://localhost:8080
```

Expected result: the default Nginx welcome page.

### Evidence for G3

Capture:

- `docker ps` showing the container and port mapping.
- The welcome page with the browser address visible.

Place the screenshots under G3.

---

## 9. G4 — Inspect and Manage a Container

Time allocation: 15 minutes.

### 9.1 Read the Logs

```powershell
docker logs dop-demo
```

Look for startup messages or browser requests.

### 9.2 Stop the Container

```powershell
docker stop dop-demo
```

List running containers:

```powershell
docker ps
```

Then include stopped containers:

```powershell
docker ps -a
```

Expected result: `dop-demo` appears in the second listing with a stopped status.

### 9.3 Start the Existing Container

```powershell
docker start dop-demo
docker ps
```

Refresh:

```text
http://localhost:8080
```

Expected result: the website is available again.

### 9.4 Remove the Practice Container

Capture the required lifecycle evidence before continuing.

```powershell
docker stop dop-demo
docker rm dop-demo
docker ps -a
```

Expected result: `dop-demo` no longer appears.

### Key Distinction

```text
docker start → starts an existing container
docker run   → creates and starts a new container
docker rm    → removes a container
```

### Evidence for G4

Capture enough output to show:

- The container stopped.
- The existing container started again.
- The container was removed.

Place the screenshots under G4.

---

## 10. G5 — Build a Custom Website Image

Time allocation: 30 minutes, including the learning checkpoint.

### 10.1 Create the Website

From your workspace:

```powershell
notepad .\site\index.html
```

If asked whether to create the file, select Yes.

Paste:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Docker Website</title>
</head>
<body>
  <h1>My Docker Website</h1>
  <p>Student initials: AB</p>
  <p>This page is served from my custom Docker image.</p>
</body>
</html>
```

Replace `AB` with your initials.

Save and close Notepad.

### 10.2 Create the Dockerfile

```powershell
notepad .\site\Dockerfile
```

Paste:

```dockerfile
FROM nginx:alpine
COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
```

Save the file as:

```text
Dockerfile
```

If using Save As, select All files so that Notepad does not append `.txt`.

Check:

```powershell
Get-ChildItem .\site
```

Expected files:

```text
Dockerfile
index.html
```

### 10.3 Understand the Dockerfile

| Instruction | Purpose |
| :--- | :--- |
| `FROM` | Selects the starting image |
| `COPY` | Copies the website into the image |
| `CMD` | Specifies the default command for containers created from the image |

### 10.4 Learning Checkpoint — Understand Before Applying

Before building, predict what one Dockerfile instruction does.

Check your prediction using this guide and the official documentation:

[Dockerfile Reference](https://docs.docker.com/reference/dockerfile/)

If you choose to use an AI/LLM tool, you may also ask it to explain the instruction in context. For example:

```text
I am completing a Docker practical using PowerShell on Windows.

My Dockerfile is:

FROM nginx:alpine
COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]

I predict that COPY places my HTML file inside the image.

Explain whether my prediction is accurate.
Identify one claim I can verify using the build and browser check
already required in this activity.

Do not suggest extra software or unrelated changes.
```

Then:

1. Compare your prediction with the explanation you consulted.
2. Identify one claim you can check.
3. Check it through the build and execution below.
4. Decide whether the explanation was accurate and useful.

If you used AI, compare its explanation with this guide or official documentation rather than relying on the AI response alone.

Keep one example in mind for your reflection.

No additional screenshot or written answer is required for this checkpoint.

### 10.5 Build the Image

From the `DOP-Docker` workspace:

```powershell
docker build -t dop-site:1.0 .\site
```

The final argument, `.\site`, is the build context: the folder containing the files used for this build.

Check the image:

```powershell
docker image ls dop-site
```

### 10.6 Run the Custom Website

```powershell
docker run -d --name dop-site -p 127.0.0.1:8081:80 dop-site:1.0
```

Check:

```powershell
docker ps
```

Open:

```text
http://localhost:8081
```

Expected result:

- Your custom heading appears.
- Your initials appear.
- The browser displays the page copied into your image.

### Evidence for G5

Capture:

- The successful build result and image listing.
- The running `dop-site` container.
- The custom webpage with your initials and browser address visible.

Place the screenshots under G5.

---

## 11. G6 — Demonstrate Named-Volume Persistence

Time allocation: 20 minutes.

A named volume stores data separately from a container’s writable layer. Its contents can remain available after that container is removed and can be mounted into another container.

Documentation:

[Docker Volumes](https://docs.docker.com/engine/storage/volumes/)

### 11.1 Create a Volume

```powershell
docker volume create dop-data
```

### 11.2 Create a Container Using the Volume

```powershell
docker run -d --name dop-store-1 --mount type=volume,source=dop-data,target=/data nginx:alpine
```

This container does not need a published website port for the storage activity.

### 11.3 Write a Message

Replace `AB` with your initials:

```powershell
docker exec dop-store-1 sh -c 'echo AB-created-this-note > /data/note.txt'
```

Read it:

```powershell
docker exec dop-store-1 cat /data/note.txt
```

Expected result, using your initials:

```text
AB-created-this-note
```

### 11.4 Inspect the Mount

```powershell
docker inspect dop-store-1 --format '{{json .Mounts}}'
```

Look for:

- Type: `volume`.
- Name: `dop-data`.
- Destination: `/data`.

### 11.5 Remove the Original Container

Capture the original message and mount evidence first.

```powershell
docker stop dop-store-1
docker rm dop-store-1
```

Check that the volume remains:

```powershell
docker volume ls
```

### 11.6 Create a Replacement Container

```powershell
docker run -d --name dop-store-2 --mount type=volume,source=dop-data,target=/data nginx:alpine
```

Read the existing file:

```powershell
docker exec dop-store-2 cat /data/note.txt
```

Expected result: the original message appears.

> Do not write the file again after replacement. Reading the existing message is the persistence demonstration.

### Evidence for G6

Capture a sequence showing:

1. The original message and volume mount.
2. Removal of `dop-store-1`.
3. The same message read through `dop-store-2`.

Place the screenshots under G6.

---

## 12. Small Applied Practical Assessment

Complete both parts.

This is a guided application of the skills practised above. Use the supplied steps, but carry out and verify the work yourself.

AI assistance is optional and permitted within the responsibilities in Section 5. Your screenshots must show your own execution.

### Part A — Build and Run an Assessment Website

Time allocation: 15 minutes.

#### A1. Create the Assessment Webpage

```powershell
notepad .\assessment\index.html
```

Paste:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Docker Applied Assessment</title>
</head>
<body>
  <h1>Docker Applied Assessment</h1>
  <p>Student initials: AB</p>
  <p>I built this page into a custom container image.</p>
  <p>One concept I practised: REPLACE THIS WITH YOUR OWN SENTENCE.</p>
</body>
</html>
```

Replace:

- `AB` with your initials.
- The final placeholder with one short, accurate sentence about your learning.

Save the file.

#### A2. Create the Dockerfile

```powershell
notepad .\assessment\Dockerfile
```

Paste:

```dockerfile
FROM nginx:alpine
COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
```

Save as `Dockerfile`, not `Dockerfile.txt`.

#### A3. Build and Run

```powershell
docker build -t dop-assessment:1.0 .\assessment
docker run -d --name dop-assessment -p 127.0.0.1:8082:80 dop-assessment:1.0
```

Verify:

```powershell
docker image ls dop-assessment
docker ps
```

Open:

```text
http://localhost:8082
```

#### Evidence for Part A

Capture:

- Successful build output and image listing.
- The running assessment container and port mapping.
- The webpage with your initials, completed learning sentence and browser address.

Place the screenshots under Assessment Part A.

### Part B — Preserve a Message Across Container Replacement

Time allocation: 15 minutes.

#### B1. Create a Separate Assessment Volume

```powershell
docker volume create dop-assessment-data
```

#### B2. Create the Original Container

```powershell
docker run -d --name dop-assess-store-1 --mount type=volume,source=dop-assessment-data,target=/data nginx:alpine
```

#### B3. Write and Read Your Message

Replace `AB` with your initials:

```powershell
docker exec dop-assess-store-1 sh -c 'echo AB-assessment-message > /data/assessment.txt'
docker exec dop-assess-store-1 cat /data/assessment.txt
```

Inspect the mount:

```powershell
docker inspect dop-assess-store-1 --format '{{json .Mounts}}'
```

#### B4. Remove the Original Container

Capture your original message and mount evidence first.

```powershell
docker stop dop-assess-store-1
docker rm dop-assess-store-1
```

#### B5. Create a Replacement and Retrieve the Message

```powershell
docker run -d --name dop-assess-store-2 --mount type=volume,source=dop-assessment-data,target=/data nginx:alpine
docker exec dop-assess-store-2 cat /data/assessment.txt
```

Expected result: your original assessment message appears.

Do not recreate or rewrite the message after replacement.

#### Evidence for Part B

Capture:

- The original message and named-volume mount.
- Removal of the original container.
- Retrieval of the unchanged message through the replacement container.

Place the screenshots under Assessment Part B.

---

## 13. Reflection

Write approximately 100–150 words covering:

1. One Docker concept you understood better through your actual work.
2. How you checked your understanding or resolved an issue using this guide, official documentation or an optional AI tool.
3. One limitation, safety consideration or improvement you would apply next time.

If you used AI, include one example of how you evaluated and verified its response.

If you did not use AI, describe how you checked an explanation or proposed solution using the guide, official documentation and your own execution.

Use specific examples from your own work.

No additional report is required.

---

## 14. AI/LLM Usage Declaration

Place a brief declaration after your reflection.

The declaration is outside the reflection’s suggested word count.

### If You Used AI

Adapt this statement accurately:

> I used [tool name] to help with [specific question or task]. I checked its response by [documentation, diagnostic check or execution]. I [used, adapted or rejected] the suggestion because [brief reason]. My screenshots show my own execution.

Acknowledge other assistance where applicable, including help with reflection wording.

### If You Did Not Use AI

> I did not use an AI/LLM tool for this practical.

You do not need to explain or justify not using AI.

No prompt transcript or conversation history is required.

---

## 15. Assessment Criteria

| Component | Criteria | Marks |
| :--- | :--- | ---: |
| Guided activities G1–G4 | Evidence of readiness, image preparation, website execution and container lifecycle operations | 20 |
| Guided activity G5 | Custom image build, running container and personalised website | 15 |
| Guided activity G6 | Original message, named-volume mount and successful retrieval after container replacement | 15 |
| Assessment Part A | Correct build and execution, required webpage content and clear verification evidence | 20 |
| Assessment Part B | Original message, container replacement and retrieval from the same named volume | 15 |
| Reflection | Specific Docker learning, verification of understanding or a proposed solution, and a meaningful limitation or improvement | 15 |
| Total | | 100 |

### Reflection Criteria

| Criterion | Marks |
| :--- | ---: |
| Explains Docker learning using a specific practical example | 5 |
| Explains how understanding or a proposed solution was checked using the guide, official documentation or an optional AI tool | 5 |
| Identifies a meaningful limitation, safety consideration or improvement | 5 |
| Total | 15 |

Students are assessed on their technical work, judgement and verification.

Using AI does not earn additional marks, and choosing not to use AI does not reduce the marks available.

If AI is used, its assistance must be acknowledged accurately.

Include the brief AI declaration whether or not you used AI.

Where technical work remains incomplete, submit the actual error and available evidence. Do not claim successful execution that the evidence does not demonstrate.

---

## 16. Troubleshooting and Using AI Effectively

Unexpected results are part of working with software. Use each result to decide what to check next.

Troubleshooting and any optional AI consultation are included within the existing activity allocations.

### 16.1 Work Through One Check at a Time

```text
Read the message
      ↓
Identify the command and expected result
      ↓
Perform a focused check
      ↓
Consult this guide or official documentation
      ↓
Optionally consult AI and evaluate its response
      ↓
Review and apply an appropriate change
      ↓
Verify the result
```

Changing one thing at a time makes it easier to identify what resolved the issue. Capture useful error messages before making changes.

### 16.2 PowerShell Does Not Recognise `docker`

1. Confirm that Docker Desktop installation has finished.
2. Close PowerShell.
3. Open a new PowerShell window.
4. Try:

```powershell
docker version
```

If the message remains, use the exact error when consulting the official installation guidance.

You may also consult AI if you choose, following Section 5.

### 16.3 Client Information Appears, but the Server Connection Fails

1. Open Docker Desktop.
2. Wait until the engine is ready.
3. Run:

```powershell
docker version
```

4. If necessary, restart Docker Desktop through its troubleshooting controls.

Start with a restart rather than data cleanup or factory reset, which may remove resources or settings.

### 16.4 WSL Is Missing or Needs Updating

Check:

```powershell
wsl --version
```

If an update is appropriate and authorised:

```powershell
wsl --update
```

If WSL is not installed, follow the official setup instructions. First-time setup can require additional permissions and a restart.

Record permission restrictions rather than attempting to bypass them.

### 16.5 A Container Name Is Already in Use

List existing containers:

```powershell
docker ps -a
```

Then choose the action that matches your intention:

- To continue using an existing stopped container, start it.
- To create a replacement, preserve required evidence and data before removing your disposable practice container.

Check the container’s name and purpose before removing it.

### 16.6 A Host Port Is Already Allocated

Check running containers:

```powershell
docker ps
```

Identify whether one of your containers uses the required port.

If appropriate, use another available host port and update the browser URL.

For example, after resolving any existing `dop-demo` name conflict:

```powershell
docker run -d --name dop-demo -p 127.0.0.1:8090:80 nginx:alpine
```

Then open:

```text
http://localhost:8090
```

The host port changes to 8090; the container port remains 80.

Keep the changed mapping visible in your evidence.

### 16.7 Docker Cannot Find the Dockerfile or HTML File

Check your working location:

```powershell
Get-Location
```

If needed:

```powershell
Set-Location "$HOME\DOP-Docker"
```

List the files:

```powershell
Get-ChildItem .\site
```

Confirm:

```text
site/
├── Dockerfile
└── index.html
```

Check that both files are saved and that the Dockerfile is not named `Dockerfile.txt`.

For the assessment build, check the `assessment` folder instead.

### 16.8 The Browser Shows an Earlier Version of the Page

Check:

1. Is the intended HTML file saved?
2. Did you build the correct source folder?
3. Did you use the intended image?
4. Did you create a replacement container after rebuilding?
5. Is the browser using the correct URL?

For this practical’s image-based workflow, saving the source file alone does not update an already-created image or container.

Preserve required evidence before replacing a container.

### 16.9 The Stored Message Is Not Available

Check:

- Whether the original writing command succeeded.
- Whether both containers use the same named volume.
- Whether the volume is mounted at `/data`.
- Whether the filename matches.
- Whether the original volume still exists.

If you correct the setup, repeat the persistence demonstration from the writing stage and capture the new results.

For a valid replacement demonstration, retrieve the existing note without writing it again after replacement.

### 16.10 Optional AI Troubleshooting Prompt

If you choose to consult AI, use a focused prompt such as:

```text
I am completing a Docker self-learning practical on Windows.

Terminal: PowerShell
Activity: [Enter the activity]

Command:
[Paste the exact command]

Error or unexpected result:
[Paste the actual message or describe the result]

Expected result:
[Explain what should happen]

Checks already completed:
[Briefly list your checks]

Please:
1. Explain the likely cause clearly.
2. Suggest one safe diagnostic check at a time.
3. Explain what each command does.
4. Identify any action that deletes data or changes system settings.
5. Keep the suggestions within authorised access and security settings.
```

Remove passwords, tokens, student identifiers and unrelated private information before sharing text or screenshots.

### 16.11 Review Suggestions Before Applying Them

Whether a suggestion comes from AI or another source, check:

- Is the command suitable for PowerShell?
- Does it use your actual folder and resource names?
- Does it remove data or change system settings?
- Do you have permission to make the change?
- Can you explain its purpose?
- How will you check whether it worked?

Compare significant changes with official documentation.

### 16.12 Record Your Outcome Honestly

If an activity remains incomplete within the allocated time:

1. Capture the actual error or current result.
2. Place it under the relevant activity heading.
3. Add a brief note identifying the unfinished step.
4. Acknowledge any AI assistance you used.

A clear record of partial progress is more useful than an unsupported claim of completion.

---

## 17. Final Submission Checklist

### Student Details

- [ ] My name, student ID and class are included.
- [ ] Website content and stored messages use my initials.

### Guided Activities

- [ ] G1 shows Docker readiness and the test container result.
- [ ] G2 shows the workspace and downloaded image.
- [ ] G3 shows the running container and welcome page.
- [ ] G4 shows the container lifecycle operations.
- [ ] G5 shows my custom build, running container and website.
- [ ] G6 shows the original message and retrieval after container replacement.

### Applied Assessment

- [ ] Part A shows the assessment image, running container and completed webpage.
- [ ] Part B shows persistence across container replacement without rewriting the message.

### Reflection and AI Declaration

- [ ] My reflection is approximately 100–150 words.
- [ ] My reflection includes specific examples of learning and verification.
- [ ] If I used AI, I evaluated and verified relevant explanations or suggestions.
- [ ] My AI/LLM declaration accurately states whether and how I used AI.

### Document Quality

- [ ] Screenshots are readable and placed under the correct headings.
- [ ] Browser addresses and relevant resource names are visible.
- [ ] Screenshots show my own execution.
- [ ] Unrelated private information is excluded.
- [ ] Any incomplete activities are identified honestly.
- [ ] I am submitting one `.docx` file only.

---

## 18. After Capturing Your Evidence

Stopping a running container does not remove it.

If you no longer need the practice containers running, stop those you created:

```powershell
docker stop dop-site
docker stop dop-store-2
docker stop dop-assessment
docker stop dop-assess-store-2
```

Run only the commands for containers that exist in your environment.

Keep the containers, images and named volumes until your evidence is complete and any retention instructions issued by the school have been met.

Removing a named volume deletes its stored data. Volume removal is separate from container removal.

---

## Official Documentation

- [Install Docker Desktop on Windows](https://docs.docker.com/desktop/setup/install/windows-install/)
- [Dockerfile Reference](https://docs.docker.com/reference/dockerfile/)
- [Docker Volumes](https://docs.docker.com/engine/storage/volumes/)
