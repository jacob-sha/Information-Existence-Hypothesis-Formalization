# Repository Setup Guide

Suggested repository name:

```text
Information-Existence-Hypothesis-Formalization
```

Suggested GitHub description:

```text
AI-assisted mathematical and theoretical modeling notes for the Information Existence Hypothesis (IEH). Author is not a professional mathematician or theoretical physicist.
```

Suggested topics:

```text
information-theory
thermodynamics
complex-systems
artificial-intelligence
evolutionary-dynamics
free-energy-principle
lotka-volterra
control-theory
information-existence-hypothesis
```

## Create the repository locally

```bash
mkdir Information-Existence-Hypothesis-Formalization
cd Information-Existence-Hypothesis-Formalization

mkdir formalization docs
touch README.md
touch formalization/01-silicon-cambrian-formalization.md
touch docs/repository-setup.md

git init
git add .
git commit -m "Initial commit: IEH formalization notes"
```

## Connect to GitHub

After creating an empty GitHub repository, run:

```bash
git branch -M main
git remote add origin https://github.com/jacob-sha/Information-Existence-Hypothesis-Formalization.git
git push -u origin main
```

If the repository name or GitHub account differs, replace the URL accordingly.


## Recommended Pinned Disclaimer

Place the following sentence near the top of the GitHub repository description, README, and each formalization note:

```text
This is an AI-assisted, author-directed exploratory modeling project. The author is not a professional mathematician, theoretical physicist, or academic theorist, and these documents are not presented as final mathematical proofs or peer-reviewed scientific papers.
```
