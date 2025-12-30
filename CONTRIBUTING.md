# CONTRIBUTING — ZERO TOLERANCE FOR MEDIOCRITY

## 🎯 PHILOSOPHY

This repository operates under **engineering supremacy principles**. Every contribution must meet or exceed existing quality standards.

## ⚠️ BEFORE YOU START

**Read this entire document.** Ignorance is not an excuse.

## 📋 CONTRIBUTION REQUIREMENTS

### 1. CODE QUALITY

- **Tests are mandatory** for all new functionality
- **Performance benchmarks** required if you claim optimization
- **Failure modes** must be documented
- **No magic numbers** — constants must be named
- **No commented-out code** — delete it or explain why it exists

### 2. DOCUMENTATION

- **README updates** required for user-facing changes
- **Architecture decisions** must be documented
- **API changes** require migration guides
- **Breaking changes** require deprecation notices

### 3. TESTING

- **Unit tests** for all business logic
- **Integration tests** for API boundaries
- **Performance tests** for optimization claims
- **Failure scenario tests** for error handling

### 4. PERFORMANCE

- **Benchmarks required** for any performance claim
- **Memory profiling** for resource-intensive changes
- **Load testing** for scalability changes

### 5. SECURITY

- **Input validation** mandatory
- **Secret management** via environment variables
- **No hardcoded credentials**
- **Security audit** for authentication/authorization changes

## 🚫 REJECTION CRITERIA

Your PR will be **REJECTED** if:

- ❌ No tests
- ❌ No documentation
- ❌ Performance claims without benchmarks
- ❌ Breaking changes without migration path
- ❌ Code without failure mode documentation
- ❌ Magic numbers or unclear naming
- ❌ Commented-out code
- ❌ No rollback plan for risky changes

## 📝 PR TEMPLATE

Use the provided PR template. All sections must be completed.

## 🧪 TESTING REQUIREMENTS

```bash
# Run tests before submitting
npm test  # or equivalent
npm run lint
npm run benchmark  # if applicable
```

## 📊 BENCHMARK REQUIREMENTS

If you claim performance improvements:

```markdown
| Metric | Before | After | Improvement |
|--------|--------|-------|-------------|
| Latency | 100ms | 50ms | 50% |
```

## 🔄 REVIEW PROCESS

1. **Self-review** — Review your own code first
2. **Automated checks** — CI must pass
3. **Manual review** — Senior engineer review
4. **Approval** — Requires 2 approvals minimum

## ⚡ FAST TRACK

PRs that include:
- ✅ Comprehensive tests
- ✅ Benchmarks (if applicable)
- ✅ Documentation
- ✅ Failure mode analysis

Will be reviewed **faster**.

## 🎓 LEARNING RESOURCES

If you're unsure about quality standards:

1. Review existing code in this repo
2. Read the Engineering Doctrine in README
3. Study the Failure Case Hall of Fame
4. Ask questions before coding

## 🚨 FINAL WARNING

**This is not a tutorial repository.**  
**This is not a learning playground.**  
**This is production-grade code.**

If you're not ready to meet these standards, **don't submit a PR.**

---

**Quality is not negotiable. Excellence is expected.**

