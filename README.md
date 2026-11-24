# SchoolSphere — School Management Portal

**Student:** D. Manoj Varma  
**Enrollment No.:** 92540118171  
**Division:** 3EN-17

A responsive, front-end school management prototype created for the AI-Assisted Web Application Project (ESE).

## Prototype modules

- Dashboard summary
- Student directory with search and add-student form
- Teacher directory
- Attendance marking
- Fee status demonstration and sample mark-paid interaction
- Notice board with create-notice form
- Responsive layout for desktop and mobile
- Browser localStorage for demo student, fee, and notice data

## Run locally

The project source is stored as a gzip-compressed Base64 file `index.html.gz.b64` to keep repository transfer compact. Open the GitHub Pages workflow to see how it decodes the page into the published site artifact. For a direct local copy, use the accompanying ESE project ZIP from the report files.

## Publish

In this repository, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**. The workflow in `.github/workflows/deploy.yml` will then deploy the site whenever a commit is pushed to `main`.

## Prototype limitations

This is an academic front-end demonstration using sample data and browser localStorage. It does not provide real authentication, shared cloud storage, or payment processing. Do not enter private student records.
