# LUCA License Guide

A comprehensive guide to understanding and using the LUCA Free License.

## Table of Contents

1. [What is LUCA?](#what-is-luca)
2. [Quick Reference](#quick-reference)
3. [For Developers](#for-developers)
4. [For Users](#for-users)
5. [Legal Summary](#legal-summary)
6. [Comparison with Other Licenses](#comparison-with-other-licenses)
7. [Resources](#resources)

## What is LUCA?

**LUCA** (Liberty Unrestricted for Creative Autonomy) is a permissive free software license that provides maximum freedom with minimal restrictions.

**Core Principle:** DO WHAT THE FUCK YOU WANT TO.

## Quick Reference

### Can I...?

| Action | LUCA | Notes |
|--------|------|-------|
| Use commercially | ✅ Yes | Zero restrictions |
| Modify the code | ✅ Yes | Any modifications allowed |
| Distribute | ✅ Yes | Original or modified |
| Sublicense | ✅ Yes | Under any license |
| Use privately | ✅ Yes | No disclosure required |
| Keep modifications private | ✅ Yes | No copyleft |
| Skip attribution | ✅ Yes | Not required (but appreciated) |
| Use in proprietary software | ✅ Yes | Fully allowed |

### Must I...?

| Requirement | LUCA | Notes |
|-------------|------|-------|
| Include license | ❌ No | Not required |
| Provide attribution | ❌ No | Not required |
| Share modifications | ❌ No | Not required |
| Use same license | ❌ No | Not required |
| Include copyright notice | ❌ No | Not required |
| State changes | ❌ No | Not required |

## For Developers

### Applying LUCA to Your Project

1. **Add the License File**
   ```bash
   curl -o COPYING https://raw.githubusercontent.com/druvx13/LUCA/main/COPYING
   ```

2. **Update Copyright**
   Edit `COPYING` and replace:
   - `[YEAR]` with current year
   - `[YOUR NAME/ORGANIZATION]` with your name

3. **Add Badge to README** (optional)
   ```markdown
   [![LUCA License](https://img.shields.io/badge/License-LUCA-blue.svg)](https://github.com/druvx13/LUCA)
   ```

### When to Choose LUCA

✅ **Choose LUCA if you want:**
- Maximum freedom for users
- No attribution requirements
- Simple, short license
- No copyleft restrictions
- Commercial-friendly terms

❌ **Don't choose LUCA if you need:**
- Required attribution
- Copyleft protection
- Detailed patent clauses
- Trademark protections

## For Users

### Using LUCA-Licensed Software

When you encounter LUCA-licensed software, you can:

1. **Use it freely** - Commercial, private, educational - any purpose
2. **Modify it** - Change the code however you want
3. **Distribute it** - Share original or modified versions
4. **Relicense it** - Release under a different license
5. **Integrate it** - Combine with any other code
6. **Keep it private** - No disclosure obligations

### No Obligations

Unlike many licenses, LUCA requires **nothing** from you:
- No attribution needed
- No license preservation required
- No modification sharing required
- No copyright notices needed

### Warranty & Liability

⚠️ **Important:** LUCA-licensed software comes with:
- **NO WARRANTY** - Use at your own risk
- **NO LIABILITY** - Authors are not responsible for damages

## Legal Summary

### Permissions

- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use
- ✅ Sublicensing
- ✅ Patent use (implicit grant)

### Conditions

- ❌ None required

### Limitations

- ❌ No liability
- ❌ No warranty

### Special Clauses

1. **Warranty Disclaimer** - Clear disclaimer of all warranties
2. **Liability Limitation** - No liability for damages
3. **Severability** - If any part is unenforceable, rest remains valid
4. **Self-Modification** - License itself can be modified

## Comparison with Other Licenses

### LUCA vs MIT

| Feature | LUCA | MIT |
|---------|------|-----|
| Attribution | Not required | **Required** |
| License notice | Not required | **Required** |
| Copyright notice | Not required | **Required** |
| Simplicity | Very simple | Simple |
| Length | Very short | Short |
| Legal review | Newer | Well-established |

**Use LUCA** if you want fewer requirements.  
**Use MIT** if you want attribution or need an established license.

### LUCA vs GPL

| Feature | LUCA | GPL |
|---------|------|-----|
| Copyleft | No | **Yes** |
| Proprietary use | ✅ Allowed | ❌ Not allowed |
| Linking | No restrictions | Restrictions apply |
| Philosophy | Maximum freedom | Share-alike |

**Use LUCA** for maximum freedom.  
**Use GPL** to ensure derivatives stay open.

### LUCA vs Apache 2.0

| Feature | LUCA | Apache 2.0 |
|---------|------|------------|
| Patent grant | Implicit | Explicit |
| Attribution | Not required | **Required** |
| License length | Very short | Long |
| Trademark | Not addressed | Protected |

**Use LUCA** for simplicity.  
**Use Apache 2.0** for explicit patent grants and trademark protection.

### LUCA vs WTFPL

| Feature | LUCA | WTFPL |
|---------|------|-------|
| Core principle | Same | Same |
| Warranty disclaimer | Explicit | Brief |
| Severability | Yes | No |
| Legal protections | More comprehensive | Minimal |

**Use LUCA** for better legal protection.  
**Use WTFPL** for radical simplicity.

### LUCA vs Unlicense

| Feature | LUCA | Unlicense |
|---------|------|-----------|
| Approach | Licensed | Public domain |
| Copyright | Maintained | Waived |
| Jurisdictions | Works everywhere | May fail in some |
| Complexity | Very simple | Very simple |

**Use LUCA** for broader legal compatibility.  
**Use Unlicense** for public domain dedication.

### LUCA vs BSD

| Feature | LUCA | BSD (2-Clause) |
|---------|------|----------------|
| Attribution | Not required | Required |
| Copyright notice | Not required | Required |
| Simplicity | Very simple | Simple |
| Endorsement clause | Not addressed | Prohibited |

**Use LUCA** for fewer requirements.  
**Use BSD** for attribution with endorsement protection.

## License Selection Decision Tree

```
Start: What do you want?

├─ Do you want to ensure derivatives stay open source?
│  └─ YES → Use GPL/AGPL (copyleft)
│
├─ Do you need explicit patent protections?
│  └─ YES → Use Apache 2.0
│
├─ Do you want trademark protections?
│  └─ YES → Use Apache 2.0 or MPL
│
├─ Do you require attribution?
│  ├─ YES → Use MIT or BSD
│  └─ NO → Continue...
│
├─ Do you want maximum freedom and simplicity?
│  └─ YES → Use LUCA ✨
│
└─ Do you want public domain dedication?
   └─ YES → Use Unlicense or CC0
```

## Detailed Comparisons

### When LUCA is Better

1. **vs MIT**: No attribution requirement
2. **vs Apache**: Simpler, shorter
3. **vs GPL**: No copyleft restrictions
4. **vs WTFPL**: Better legal protections
5. **vs Unlicense**: Works in more jurisdictions

### When Other Licenses are Better

1. **MIT better than LUCA**: Need established license, want attribution
2. **Apache better than LUCA**: Need explicit patent clauses, trademark protection
3. **GPL better than LUCA**: Want to ensure derivatives stay open
4. **BSD better than LUCA**: Need endorsement protection clause
5. **Unlicense better than LUCA**: Want true public domain dedication

## Legal Analysis by Jurisdiction

### United States

LUCA is valid under US copyright law:
- Warranty disclaimer meets legal standards
- Severability clause is enforceable
- Permission grant is clear
- No public policy violations

### European Union

LUCA works across EU:
- Complies with copyright directives
- Warranty disclaimer valid
- GDPR neutral (doesn't address data)
- Severability ensures local adaptability

### United Kingdom

Post-Brexit, LUCA remains valid:
- Meets UK copyright requirements
- Warranty exclusions enforceable
- Contract principles satisfied

### Australia

LUCA is enforceable:
- Complies with Copyright Act 1968
- Disclaimer meets Australian Consumer Law standards
- Clear permission grant

### Canada

LUCA works under Canadian law:
- Meets Copyright Act requirements
- Warranty disclaimer valid
- Quebec civil code compatible

### Japan

LUCA is valid:
- Complies with Japanese Copyright Law
- Translation available (unofficial)
- Severability ensures enforceability

### India

LUCA is enforceable:
- Meets Indian Copyright Act requirements
- Warranty disclaimer valid
- Growing FOSS community adoption

**Note:** This is general guidance. For specific legal questions, consult local counsel.

## Resources

### Documentation
- [README](README.md) - Project overview
- [ABOUT](ABOUT.md) - Philosophy and background
- [FAQ](FAQ.md) - Frequently asked questions
- [USAGE](USAGE.md) - Detailed usage guide
- [BADGES](BADGES.md) - Badge examples
- [CONTRIBUTING](CONTRIBUTING.md) - How to contribute
- [CHANGELOG](CHANGELOG.md) - Version history

### Website
- **Main Site:** https://druvx13.github.io/LUCA/
- **About Page:** https://druvx13.github.io/LUCA/about.html
- **Usage Guide:** https://druvx13.github.io/LUCA/usage.html
- **FAQ:** https://druvx13.github.io/LUCA/faq.html

### License Text
- [COPYING](COPYING) - Full license text

### GitHub
- **Repository:** https://github.com/druvx13/LUCA
- **Issues:** https://github.com/druvx13/LUCA/issues
- **Discussions:** https://github.com/druvx13/LUCA/discussions

## Advanced Topics

### License Compatibility Matrix

| LUCA + | Compatible? | Notes |
|--------|-------------|-------|
| MIT | ✅ Yes | Both permissive |
| BSD | ✅ Yes | Both permissive |
| Apache 2.0 | ✅ Yes | Both permissive |
| GPL v2 | ⚠️ Complex | GPL is copyleft |
| GPL v3 | ⚠️ Complex | GPL is copyleft |
| AGPL | ⚠️ Complex | AGPL is copyleft |
| LGPL | ✅ Generally | For library linking |
| MPL | ✅ Yes | File-level copyleft OK |
| WTFPL | ✅ Yes | Both maximally permissive |
| Unlicense | ✅ Yes | Both permissive |
| CC0 | ✅ Yes | Both permissive |
| Proprietary | ✅ Yes | LUCA allows this |

**Legend:**
- ✅ Yes: Fully compatible
- ⚠️ Complex: Possible but requires careful consideration
- ❌ No: Incompatible

### Combining Code

When combining code with different licenses:

1. **LUCA + Permissive (MIT/BSD/Apache)**: Use most restrictive terms (usually the other license)
2. **LUCA + Copyleft (GPL)**: Must follow GPL terms for combined work
3. **LUCA + Proprietary**: Fully allowed, can make proprietary
4. **LUCA + LUCA**: Perfect compatibility

### Inbound vs Outbound Licensing

**Inbound** (accepting contributions):
- Contributors grant you LUCA rights
- No CLA needed
- Implicit LUCA licensing

**Outbound** (distributing):
- You can distribute under LUCA or any other license
- No restrictions from LUCA
- You control distribution terms

### Special Use Cases

#### Academic Research
- ✅ Perfect for research code
- ✅ No attribution burden
- ✅ Allows commercial use of research
- ⚠️ Consider citation in papers (ethical, not legal)

#### Government Projects
- ✅ Suitable for government code release
- ✅ No ongoing obligations
- ⚠️ Some agencies prefer established licenses

#### Medical/Safety Critical
- ⚠️ Warranty disclaimer may not be sufficient
- ⚠️ Consider specialized licenses
- ⚠️ Regulatory compliance separate from license

#### Financial Software
- ✅ Legally permissible
- ⚠️ Industry regulations separate from license
- ⚠️ Audit requirements independent

## Quick Links

- 🏠 [Home](https://druvx13.github.io/LUCA/)
- 📖 [Documentation](README.md)
- ❓ [FAQ](FAQ.md)
- 🚀 [Usage Guide](USAGE.md)
- 🏷️ [Badges](BADGES.md)
- 💬 [GitHub Issues](https://github.com/druvx13/LUCA/issues)

---

**LUCA Free License v1.0**  
**DO WHAT THE FUCK YOU WANT TO.**

Licensed under LUCA v1.0 - Copyright (C) 2026
