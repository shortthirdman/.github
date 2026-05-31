<!-- 
Thanks for creating this pull request 🤗

Please make sure that the pull request is limited to one type (docs, feature, etc.) and keep it as small as possible. You can open multiple prs instead of opening a huge one.
-->

# 🚀 Pull Request

## 📌 Summary
<!--
Provide a concise summary of the change.
Focus on *what* and *why*, not implementation details.
-->

---

## 📑 Description

<!--
You can also choose to add a list of changes and if they have been completed or not by using the markdown to-do list syntax
-->
- [ ] Not Completed
- [ ] Completed

---

## 🧩 Type of Change
<!-- Select all that apply -->
- [ ] 🔬 Research / Experiment
- [ ] ✨ New feature
- [ ] 🐛 Bug fix
- [ ] ♻️ Refactor (no functional change)
- [ ] ⚡ Performance improvement
- [ ] 🛠️ Build / CI / Tooling change
- [ ] 🔐 Security fix
- [ ] 🧪 Test-only change
- [ ] 📚 Documentation update
- [ ] 🚢 Production release change

---

## 🧪 Research vs Production Readiness
<!-- Required to support internal research → production flow -->
- [ ] This PR is **research / experimental only**
- [ ] This PR is **production-ready**
- [ ] This PR transitions research code toward production

**Notes (if applicable):**
<!-- Call out experimental assumptions, limitations, or follow-ups -->

---

## 🧾 Conventional Commit Compliance
<!-- semantic-release relies on this -->
- [ ] PR title follows **Conventional Commits**
  - Examples:
    - `feat(api): add rate limiting`
    - `fix(ci): resolve flaky pipeline`
    - `chore(deps): bump terraform provider`
- [ ] Commit messages are clean, meaningful, and scoped
- [ ] No breaking changes OR breaking changes are documented below

### ⚠️ Breaking Changes (if any)
```text
Describe the breaking change and required migration steps
```

---

## 🔄 CI/CD & GitOps Checklist

<!-- These checks ensure automation safety -->

* [ ] CI pipeline passes locally and in GitHub Actions
* [ ] Linting, formatting, and static analysis pass
* [ ] Tests added or updated (unit / integration / e2e)
* [ ] No secrets, credentials, or tokens committed
* [ ] Versioning handled **only** via semantic-release (no manual bumps)
* [ ] GitOps manifests updated (if applicable)
* [ ] Rollback strategy considered

---

## ✅ Checks
<!-- Make sure your pr passes the CI checks and do check the following fields as needed - -->
- [ ] My pull request adheres to the code style of this project
- [ ] My code requires changes to the documentation
- [ ] I have updated the documentation as required
- [ ] All the tests have passed

---

## 🏗️ Infrastructure / Deployment Impact

<!-- Skip if not applicable -->

* [ ] No infrastructure changes
* [ ] Kubernetes / Helm / Argo / Flux changes
* [ ] Terraform / Cloud resource changes
* [ ] Environment variables or secrets updated

**Details:**

<!-- Describe blast radius, environments affected, and rollout strategy -->

---

## 🧪 Testing Strategy

<!-- Be explicit for reviewers and automation -->

* [ ] Unit tests
* [ ] Integration tests
* [ ] End-to-end tests
* [ ] Manual testing performed

**Test evidence / commands run:**

```bash
# example
make test
```

---

## 📊 Observability & Ops Readiness

<!-- Required for production-facing changes -->

* [ ] Logging updated (if applicable)
* [ ] Metrics / alerts added or updated
* [ ] Dashboards validated
* [ ] Error handling reviewed

---

## 🔐 Security & Compliance

* [ ] Security impact reviewed
* [ ] Dependency scan passed
* [ ] No new high/critical vulnerabilities introduced
* [ ] Access control / RBAC reviewed (if applicable)

---

## 📚 Documentation

* [ ] Code comments added/updated
* [ ] README / docs updated
* [ ] Runbooks or ADRs updated (if applicable)

---

## 🔗 Related Issues / PRs

<!-- Use GitHub keywords: Fixes #123 -->

* Fixes #
* Related to #
* Closes # <!-- Issue # here -->

---

## 👀 Reviewer Notes

<!-- Anything specific reviewers should focus on -->

---

## ℹ Additional Information

<!-- Any additional information like breaking changes, dependencies added, screenshots, comparisons between new and old behavior, etc. -->
